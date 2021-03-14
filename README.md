# Aerial Image Dataset
![Alt Text](https://github.com/anonuser02/AerialImageDataset/blob/main/sample.png) 

Download link (GDrive): ...

The dataset comprises 2375 high-resolution aerial images captured from drones over Trujillo city in Peru. Each image has a ground resolution of ... cm per pixel. The dataset was split into training and test data using 98% and 2%, respectively, for a total of 2327 training images and 48 test images. The 48 test images were labelled manually using photoshop and QGIS.

The images are RGB JPGs and the labels are TIFFs with 3 colors representing the 3 classes (documented below).

Here are some examples of labelled images:
<p align="center">
  <img width="540" height="360" src="https://github.com/anonuser02/AerialImageDataset/blob/main/out.gif" alt="animated">
</p>

Color (Red, Green, Blue) to Class Name:
---
```
(255, 106, 000) : STRUCTURE
(255, 238, 000) : ROAD
(094, 000, 255) : TERRAIN 
```

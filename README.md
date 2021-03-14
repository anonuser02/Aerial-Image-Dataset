# Trujillo Aerial Image Dataset
![Alt Text](https://github.com/anonuser02/AerialImageDataset/blob/main/sample.png) 

Download link (baidu): https://pan.baidu.com/s/1WtHQsb73rLa-cZpBLi2dtg <br />
Download link (dropbox): https://www.dropbox.com/s/a0lj1ddd54ns8qy/All-Age-Faces%20Dataset.zip?dl=0

Contact: Jingchun Cheng (chengjingchun at gmail dot com)


The All-Age-Faces (AAF) Dataset contains 13'322 face images (mostly Asian) distributed across all ages (from 2 to 80), including 7381 females and 5941 males.

The orignal face images, facial landmarks and aligned face images are stored in folder `original images`, `key points`, and `aligned faces`, respectively. 
We show an example of landmark distribution in folder `example`.

Each image contains a different individual, and is given a unique name (`%05dA%02d.jpg`), illustrating the individual’s serial number and specific age.
Individuals from serial number 00000 to 07380 are all female, from 07381 to 13321 are male.

This dataset can be used for age prediction and gender classification. 
For fair comparison, we randomly split the images into two sets, one for trainning and the other for validation.
The annotation files in folder `image sets` have the following format:
`"%05dA%02d %d\n", person_id, age, gender,`
where for gender, 0 stands for female and 1 stands for male.

# Dataset 4C

The Dataset4C.hdf5 file consists in 396 images in RGB scale, divided in 4 classes. There are 277 training images, 59 validation images and 60 test images. (70% for training, 15% for validation and 15% for testing)

The images are getting from
https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia 
and
https://github.com/ieee8023/covid-chestxray-dataset

    Author: Sergio Luis Beleño Díaz
    Date: 2020-04-02

The classes are:

    Normal: 99
    Pneumonia Vir: 99
    Pneumonia Bact: 99
    COVID-19: 99

Labels:

    Normal ==> 0
    Pneumonia Vir ==> 1
    Pneumonia Bact ==> 2
    COVID-19 ==> 3
    
Size:

    (512,512,3)
    

<img src="índice.png" />


# How to implement it

You can find an example of implementation in the following link: 
https://github.com/Serbeld/Dataset-4C/blob/master/Data_4C.ipynb

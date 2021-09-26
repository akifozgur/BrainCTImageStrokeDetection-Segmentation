# BrainCTImageStrokeDetection-Segmentation
This project firstly aims to classify brain CT images using convolutional neural networks. In the second stage, the task is making the segmentation with Unet model.
Project includes 8 different phases:

1-Working with DICOM files, getting the images in a correct way to be able to classify/segment it easily with Deep Learning methods.

2-Creating datasets with the correct structure to use them in the project.

3-Making some required operations to images such as contouring-cropping, removing noise and centering brains to convert them into a standart format.

4-Making the operations suitable to the specific task , e.g centering is not suitable to segmentation task.

5-Making different augmentations for the two separate task.

6-Constructing the models.

7-Training/testing the models.

8-Choosing the best model.



![hemorrhagicalExample](https://user-images.githubusercontent.com/56753978/134818932-b6023adb-9eaf-4af3-9d30-d397a9ecb119.png)

Segmentation of hemorrhagical stroke.

![ischemicExample](https://user-images.githubusercontent.com/56753978/134818936-ed268041-50c0-4f1f-bf8b-55273bdd142e.png)

Segmentation of ischemic stroke.

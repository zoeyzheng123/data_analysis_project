# Dog Breed Classifier 
PyTorch implementation of a dog breed classifier using convolutional neural nets. This is part of the Udacity's Deep Learning Nanodegree program projects. 

## Datasets
The dataset contains 8352 images in total, with 133 breeds. The data provided by Udacity is already split in training, validation, and test sets located in /dog_images/train, /dog_images/valid and /dog/images/test. 

Download the dog dataset. Unzip the folder and place it in this project's home directory, at the location /dogImages.
Download the human dataset. Unzip the folder and place it in the home directory, at location /lfw.

Note: If you are using a Windows machine, you are encouraged to use 7zip to extract the folder.



## Packages
The app needs the following packages in order to run 
torch(torchvision, torch.nn, torch.nn.functional, torchvision.models), ImageFile, os, matplotlab, numpy
Please add *ImageFile.LOAD_TRUNCATED_IMAGES = True* so image is allowed to be truncated


## Contents
The repository consists of the following main files:
1. dog_app.ipynb: The Udacity project. It consists of the following steps:
    * Data download and exploration 
    * introduce and implement human face detector 
    * introduce, design and implement dog detector 
    * Design, implement and test your CNN from scratch, including data loaders for train test and valid data, creterion and optimizer etc 
    * Design, implement and test your CNN using transfer learning, including data loaders for train test and valid data, creterion and optimizer etc
    * Design dog breed app
    * test dog breed app with your images!
2. model_scratch.pt
The pretrained CNN created from scratch 
3. model_transfer.pt
The pretrained CNN based on ResNet using transfer learning 

    
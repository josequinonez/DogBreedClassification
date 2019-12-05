# DogBreedClassification
Classification analysis of dog breeds using Convolutional Neural Networks (CNN)

This is a project assignment at **Udacity Deep Learning Nanodegree** program.

The project objective is to accept any user-supplied image as input and classify the image accoding to the training learned. If a dog is detected in the image, it will provide an estimate of the dog's breed. If a human is detected, it will provide an estimate of the dog breed that is most resembling.

The project scope includes both strategies to classify dog breeds: to create a CNN from scratch, and to create a CNN using Transfer Learning.

### Required data:

- Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.
- Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 

### Required libraries:
- numpy
- glob
- cv2
- matplotlib
- tqdm
- torch
- torchvision
- PIL
- os

### Lessons learned
After more than 140 epochs the CNN model created from scratch reached a test accuracy of 13%, while the model created using Transfer Learning reached 63% with only 13 epochs.

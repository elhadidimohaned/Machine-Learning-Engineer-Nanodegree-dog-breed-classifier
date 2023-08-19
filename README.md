[//]: # "Image References"

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./Certificate.png "Nano Degree Completion"

# Dog Breed Classifier Capstone Project
![Nano Degree Completion][image2]

## Project Overview

The aim of the project is to build a pipeline to process real-world, user-supplied images. A convolutional neural network (CNN) will identify an estimate of the dog's breed given an image. When the image is of a human, the CNN will choose an estimate of a dog breed that resembles the human. If neither a dog or a human is detected, then an error message is output. Therefore, the models in place should be capable of detecting a dog or human in an image, classify the dog to its breed and classify a dog breed that the human resembles. 

![Sample Output][image1]


## Dependencies

This project mainly makes use of Python, Jupyter Notebooks, OpenCV and PyTorch.

## Dependencies

The dataset used here are provided by Udacity and is similar to Stanford Dog Dataset.The dataset is saved under S3 in Amazon Web Service.

This link https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip provides the images for human and can be used to train a human face detector.

This link https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip provides the images for dog and can be used to training of dog related model.

## Submission

1. report.pdf
2. proposal.pdf
3. README.md
4. dog_app.ipynb

## Model Evaluation

The CNN model created using transfer learning with ResNet152 architecture, and the final model produced an accuracy of 85% on test data. The model correctly predicted breeds for 714 images out of 836 total images.

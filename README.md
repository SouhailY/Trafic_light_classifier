# Trafic light classifier

In this project, we’ll use computer vision techniques to build a classifier for images of traffic lights! We'll be given a dataset of traffic light images in which one of three lights is illuminated: red, yellow, or green. You will need cv2 which is a computer vision library to be able to go through the jupyter notebook.

In this notebook, we'll pre-process these images, extract features that will help us distinguish the different types of images, and use those features to classify the traffic light images into three classes: red, yellow, or green. 

**In order to be able to run the code you will have to first unzip the folder "traffic_light_images". It contains the training and test images.**

The tasks will be broken down into a few sections:

1. **Loading and visualizing the data**. 
      The first step in any classification task is to be familiar with data; we'll need to load in the images of traffic lights and visualize them!
2. **Pre-processing**. 
    The input images and output labels need to be standardized. This way, we can analyze all the input images using the same classification pipeline, and we know what output to expect when we eventually classify a *new* image. 
3. **Feature extraction**. 
    Next, we'll extract some features from each image that will help distinguish and eventually classify these images. In this case we will be using brightness feature using [HSV color space](https://en.wikipedia.org/wiki/HSL_and_HSV).
4. **Classification and visualizing error**. 
    Finally, we'll write one function that uses our feature to classify *any* traffic light image. This function will take in an image and output a label. We'll also be given code to determine the accuracy of the classification model.       
5. **Evaluate the model**.
    To pass this project, the classifier must be >90% accurate and never classify any red lights as green for safety reasons.
   

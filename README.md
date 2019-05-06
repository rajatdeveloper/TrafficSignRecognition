# TrafficSignRecognition

## Dependecies
1. OpenCv2
2. Python3
3. Tensorflow Object detection API
4. Python3
5. Keras
6. Tensorflow
7. Pandas
8. Pickle
9. Numpy

## Flow of the project
Step 1. Traffic image detection(using tensorflow object detection API)  
Step 2. Extracting the traffic sign and reshaping to 32x32.
Step 3. Loading the traffic sign classification model(trained_model.h5) and signnames.csv.
Step 4. making predictions on the extracted image.

## Note
In order for object detection to work, you also need to download Pretrained weights for object detection from [Google drive]( https://drive.google.com/open?id=1emIiAYp4tLYG0cmI8Tm2lOX5Qd47F5-8)

You can have a look at colab notebook here
https://colab.research.google.com/drive/1lVRRThKluJuEJ0UX2UxGByORsVe1b9qU#scrollTo=cFU8IAEiJk2T

### To get the Information about Traffic sign classification (CNN model and augmentation techniques used), refer to Classification folder in this repository.

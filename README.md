# Face and Eye Detection
live face and eye detection and tracking in Python using OpenCV. 
## Technologies used:
Jupyter,OpenCV,Haar-cascade classifier

## Classifier used : Haar-cascade
OpenCV provides a training method (see Cascade Classifier Training) or pretrained models, that can be read using the cv::CascadeClassifier::load method. The pretrained models are located in the data folder in the OpenCV installation or can be found here.

The following code example will use pretrained Haar cascade models to detect faces and eyes in an image. First, a cv::CascadeClassifier is created and the necessary XML file is loaded using the cv::CascadeClassifier::load method. Afterwards, the detection is done using the cv::CascadeClassifier::detectMultiScale method, which returns boundary rectangles for the detected faces or eyes.

![pic1](https://user-images.githubusercontent.com/61883605/130300950-72f95f80-aa0e-4e4e-9de6-4a1d45241af5.JPG)

Description:
Blue rectangle shows the face and Two small green rectangles shows the eyes on the frame captured by webcam.


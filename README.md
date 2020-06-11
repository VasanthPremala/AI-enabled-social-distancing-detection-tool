# AI-enabled-social-distancing-detection-tool

An AI based Tool to help out Social Distancing in the Community and Workplace.

In the fight against the coronavirus, social distancing has proven to be a very effective measure to slow down the spread of the disease. While millions of people are staying at home to help flatten the curve, many customers in the manufacturing and pharmaceutical industries are still having to go to work everyday to make sure our basic needs are met.

To help ensure social distancing protocol in their workplace, I have developed an AI-enabled social distancing detection tool that can detect if people are keeping a safe distance from each other by analyzing real time video streams from the camera.

The demos below will help to visually explain the approach that consists of three main steps:

Detect the humans in the frame with yolov3 convolutional neural network.
Calculate the distance between all the instances of humans detected in the frame.
Classify the determined distances as 'Alert' or 'Ok' for social distancing.
Output (Image)
screenshot

Requirements:

1.Numpy
2.Time
3.OpenCV
4.OpenCV_Contrib
5.Math

Installation of Model:

1.To deploy algorithm on images, python SDD_Image.py
2.To deploy algorithm on videos, python SDD_Video.py
3.To deploy algorithm on live streaming webcam, python SDD_Camera.py

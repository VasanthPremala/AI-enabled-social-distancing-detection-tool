# AI-enabled-social-distancing-detection-tool

An AI based Tool to help out Social Distancing in the Community and Workplace.

To help ensure social distancing protocol in their workplace, I have developed an AI-enabled social distancing detection tool that can detect if people are keeping a safe distance from each other by analyzing real time video streams from the camera.This will work for image,video and camera.

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


Download yolov3.weights for COCO dataset using this link https://pjreddie.com/darknet/yolo/

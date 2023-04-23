# Object Detection App Backend Documentation

## Introduction

This Node.js backend is built using the Express framework and is responsible for performing object detection on the input data received from the React Native Expo app. The backend uses the TensorFlow Object Detection API to detect objects in images and videos and returns the results to the app in a specified format.

## Installation

To install the backend do the following steps

Clone the repository from GitHub: https://github.com/cse210001015/Object-Detection-App-Backend

Navigate to the project directory using a terminal window.

Run the following command to install the necessary dependencies:

npm install

Start the backend using the following command:

node index.js

The backend is now running and listening for incoming requests from the app.

##  Object Detection Algorithm

The backend uses the TensorFlow Object Detection API to detect objects in images and videos. The API provides pre-trained models for object detection that can be fine-tuned or used directly for specific use cases. The backend loads the model and performs object detection on the input data, returning the results in the specified output format. The model used is coco ssd which has an apache licence.

## Custom Algorithm

Convert the tensorflow model to tfjs and use load graph model to load the custom model and use it for inferences.

## Troubleshooting

If you encounter any issues while using the backend, try the following troubleshooting steps:

Ensure that you have the latest version of the backend installed.

Check that the app is sending valid input data in the request body.

Ensure that the input data is in a supported format.

Check that the pre-trained model is loaded and functioning correctly.

Check that the output format is correctly specified in the app request.

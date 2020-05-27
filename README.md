# self-driving-car

#Problem Definition--Traffic Sign Benchmark
The German Traffic Sign Benchmark is a multi-class, single-image classification  problem

Single-image, multi-class classification problem
More than 40 classes
More than 50,000 images in total
Large, lifelike database


#Problem Definition
We are here building a minimal version of self driving car. Here, we have a front camera view. This will transfer input to 
the computer. Then Deep Learning algorithm in computer predicts the steering angle to avoid all sorts of collisions. 
Predicting steering angle can be thought of as a regression problem. We will feed images to Convolutional Neural Network and 
the label will be the steering angle in that image. Model will learn the steering angle as per the turns in the 
image and will finally predicts steering angle for unknown images.

#Dataset
Refer this: https://github.com/SullyChen/Autopilot-TensorFlow

There are total 45406 images in the dataset along with their steering angles. We will split the dataset into train and test in a ratio of 80:20 sequentially.
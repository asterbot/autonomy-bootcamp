<h1 align="center">Image Recognizer </h1>
<br>
<h4 align="center">Efficient Image Recognition with Keras: Harnessing Deep Learning for Accurate Visual Classification</h4>

## Description and Aim
This project was created as a submission to the WARG autonomy BootCamp.
<br>This project aims to create a **Convolutional Neural Network(CNN)** which trains based on data in the CIFAR-10 dataset
<br>and have high accuracy while testing on unknown images
<br>The CIFAR-10 dataset contains images of 10 classes (plane,car ,deer ,etc.) which the network is trained on

## Structure of the Network
The network has the following structure (in order):
- Input Layer
- First convolutional layer (conv1)
- Second convolutional layer (conv2)
- Third convolutional layer (conv3)
- Three fully connected layers (fc1, fc2, fc3)
- Output Layer

## Result
The network performed well and was able to acheive an accuracy of ~85%
<img src = "accuracy.png">
<img src="losses.png">
The exact values can be seen in `output.txt`

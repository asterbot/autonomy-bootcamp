<h1 align="center">Keras Image Classifier</h1>
<h4 align="center">Efficient Image Recognition with Keras: Harnessing Deep Learning for Accurate Visual Classification</h4>

## Description and Aim
- This project was created as a submission to the WARG autonomy BootCamp.
- This project aims to create a **Convolutional Neural Network(CNN)** which trains based on data in the CIFAR-10 dataset and have high accuracy while testing on unknown images
- The CIFAR-10 dataset contains images of 10 classes (plane,car,deer,...etc.) which the network is trained on
- The dataset was split into training data(60,000 images) and testing data(10,000 images)
- The network was trained to fit the training images and was tested on all the testing images on each epoch
- The loss function used to train was the CrossEntropyLoss, which is $\sum\limits_{i}t_i \log(p_i)$ where $t_i$ is the truth label and $p_i$ is the softmax probability of the ith class, for each element in the training data
- The optimizer used to train was Adam, which is a Scholastic Gradient Descent(SGD) method based on adaptive estimations
- To avoid overfitting, extra convolutional layers were added in the network
  
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
<table>
  <tr>
    <th>Accuracy</th>
    <th>Loss</th>
  <tr>
    <td><img src = "accuracy.png"></td>
    <td><img src="losses.png"></td>
  </tr>
</table>

<br>The exact values can be seen in the [output file](output.txt)

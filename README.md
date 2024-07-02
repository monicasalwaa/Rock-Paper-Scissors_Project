# Rock-Paper-Scissors_Project

In this exercise I had to train the model in a browser using my webcam by showing the webcam hand movements in the form of Rock, Paper, Scissors, Lizard, and Spock. Previously, the model was designed with a Convolutional Neural Network (CNN) to detect sign language using computer vision. Computer vision refers to the ability of a computer system to acquire, process, and analyze visual data from the real world. 

The model is built in Visual Studio Code and run in the Chrome browser using Web Server.  After training the model, and successfully running the code, the code will automatically download the resulting model and its weights to the download folder.

### The elements:

1. **Webcam Setup & Capture**

The code uses a webcam to capture images in real-time, which is the primary visual data source.

2. **Pre-trained Model (MobileNet)**

It uses MobileNet and uses certain layers of this model to generate features from the image captured by the webcam.

3. **Predictions with Images from Webcam**

The prediction part of the model captures images from the webcam, processes them through MobileNet to obtain features, and then uses a custom model to perform hand gesture classification.

4. **Training Process and Using Features from Images**

Images captured by the webcam are used to train the model and add new examples to the dataset.

5. **Convolution for Feature Extraction**

The convolutional layers (tf.layers.conv2d) in the model are used to process images and extract relevant visual features, which is the essence of computer vision.

Computer vision in this code is seen from the use of a webcam to capture images, the use of MobileNet for feature extraction from images, and image processing with convolutional layers in a custom model to detect sign language.

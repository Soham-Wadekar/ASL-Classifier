# ASL-Classifier

### American Sign Language
American Sign Language is a natural language that serves as the predominant sign language of Deaf communities in the United States of America and most of Anglophone Canada. ASL is a complete and organized visual language that is expressed by employing both manual and nonmanual features.

![image](https://github.com/Soham-Wadekar/ASL-Classifier/assets/108048367/a25898e2-75e4-4fda-9680-46c902250b9a)

### Dataset
The dataset that I have used is [MNIST Sign Language dataset](https://www.kaggle.com/datasets/datamunge/sign-language-mnist) from Kaggle where the images are 28×28 grayscale images. The data is stored in .csv format and has 784 pixel value columns from 0 to 255 and 1 label column ranging from 0-25(A-Y)

### Model
The model that I created is a simple Convolutional Neural Network using Tensorflow library. It is a sequential model using a couple of convolutions followed by a MaxPool.

![image](https://github.com/Soham-Wadekar/ASL-Classifier/assets/108048367/fd053b2c-cb9e-497e-9f27-0272596bc8b8)

### In this repository
In this repository, I have included the code, the model that I have built and also the dataset for those who want to implement the code for themselves. Additionally, in the code, I have created the feature to upload your own image and test it out for yourself.

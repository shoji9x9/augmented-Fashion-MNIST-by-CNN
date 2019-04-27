# Overview
This is just a example to train Fashion-MNIST by Convolutional Neural Network for learning TensorFlow 2.0.

# Description
* This is an assignment of [Deep Learning basic class](https://deeplearning.jp/lectures/dlb2018/) arranged a little. 
* Training Fashion-MNIST by CNN on Google Colaboratory with TensorFlow 2.0 Alpha.
* Data is augmented by ImageDataGenerator of Keras and the effectiveness of data augmentation is shown.

# Attention
Fashion-MNIST-by-CNN-with-data-augmentation.ipynb file can not be opened correctly, I'm not sure about the reason though. However, you can see the code in Google Colaboratory. So please take a look at [How-to-open-ipynb-on-Google-Colaboratory](https://github.com/shoji9x9/How-to-open-ipynb-on-Google-Colaboratory) and open it in Google Colaboratory.

# Dataset
This dataset can be found [here](https://github.com/zalandoresearch/fashion-mnist).

# Model
4 Layer CNN with Max Pooling, Batch Normalization and Dropout.

# Accuracy
* with Data Augmentation  
92.2% after training in 80 epochs
* witout Data Augmentation  
91.8% after training in 80 epochs  
![image](https://user-images.githubusercontent.com/40084422/56845892-d7083080-6902-11e9-9c49-c319101debd2.png)

# How to open it on Google Colaboratory
Please take a look at [How-to-open-ipynb-on-Google-Colaboratory](https://github.com/shoji9x9/How-to-open-ipynb-on-Google-Colaboratory).

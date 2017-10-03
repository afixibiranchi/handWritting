# handWritting
[![Contact](https://img.shields.io/badge/contact-gelopfalcon-orange.svg)](https://twitter.com/@gelopfalcon)
[![License](https://img.shields.io/github/license/mashape/apistatus.svg)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/lang-Swift-yellow.svg?style=flat)](https://developer.apple.com/swift/)
Example of how to use CoreML IOS.
This is the implementation of Number recognition using Keras-MNIST model on Apple's CoreML Framework.

The app fetches image from your hand writing and perform number recognition in real-time.

# Requirements
* Xcode 9
* IOS 11
* For training: Python 2.7 (Keras 2.0.4, TensorFlow 1.1, CoreMLTools 0.4.0)

# Training
If you want to train your own custom model, follow the tutorial given below to create an anaconda environment. Enter the environment and run the following commands in terminal with ./mkeras as master directory.
```ruby
    python train.py
    sudo python convert.py
```
# Tutorial
If you are interested in training your custom MNIST model from scratch, a step-by-step tutorial is available at - https://medium.com/@gelopfalcon/creating-an-ios-app-with-core-ml-from-scratch-b9e13e8af9cb
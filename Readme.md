# Project Title
This approach – Gradient-weighted Class Activation Mapping (Grad-CAM), uses the gradients of any target concept (say ‘dog’ in a classification network or a sequence of words in captioning network) flowing into the final convolutional layer to produce a coarse localization map highlighting the important regions in the image for predicting the concept.

Examples 

![image](/Users/anmolchalise/Desktop/AI_ML_model/GradCam/images/lion_tiger.png)

![Guided Grad Cam](/Users/anmolchalise/Desktop/AI_ML_model/GradCam/images/mask_cat_dog.png)


## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Credits](#credits)
- [Refrences](#refrences)


## Installation

input_image_path: Path to the input image.
input_sz: Input image size. Default is 224
model: default model ResNet50. 
layer_name : By default i have used last layer of ResNet50. If you want to explicitly use any convolutional layer just pass that   layer   name as last_conv_layer_name.(use relu5_4 for VGG-19 and relu5 for AlexNet)


## Usage
Download  VGG-16/VGG-19/AlexNet using tf.keras.applications.VGG16/GG-19/AlexNet.


## Credits
Libraray Used: Tensorflow

## Refrences

Grad-CAM: Visual Explanations from Deep Networks via Gradient-based Localization
Ramprasaath R. Selvaraju · Michael Cogswell · Abhishek Das · Ramakrishna Vedantam · Devi Parikh · Dhruv Batra


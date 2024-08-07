# Project Name
Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Load the data set of images using keras preprocessing
- Build base CNN model and visualize the training and validation accuracy
- Use data augmentation technique such as rotation flip and zoom. Fit the model and assess the impact
- Apply more techniques such as learning rate scheduling, batch normalization, architecture changes to improve the model
- Assess the class imbalance - use the augmentor to add more images and improve the class imbalance
- Build the model, fit to train and validation data and predict on the test data

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Initially the model tends to overfit the training data and gives a poor accuracy on the validation data
- Addition of the augmentor layer helped to improve the overfitting, but reduced the accuracy
- Use of learning rate scheduling did not help to improve the accuracy
- Significant class imbalance was observed an the augmentor package was used to add more images to the data set
- Adding batch normalization without the augmentation layer causes an overfitting of the model
- Model with batch normalization and data augmentation layer gives an accuracy of around 60% with the adam optimizer and sgd optimizer. The test accuracy is around 43%
- Further experimented with using L2 regularization without the augmentation layer - it led to overfitting on the train data


## Contact
Created by [@githubusername] - feel free to contact me!


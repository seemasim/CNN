# Project Name
>To build a  multiclass classification model using a custom convolutional neural network in TensorFlow. This model should aim to accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
> A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* General Information 
* Technologies Used: Python-Tensorflow and Keras 
* Conclusions
* Acknowledgements


## General Information
- We have created a  multiclass classification model using a custom CNN model using image augmentation, class balance and batch normalization on the hidden layers to correctly predict the type of skin problems.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
- After tuning the hyperparameters and adding hidden layers to CNN model, reached to a stable CNN model which can predict the class of the oncological disease with ~85% on training data and ~69% on validation data. 


## Conclusions
- The data augmentation has improved on the overfitting to some extent but the accuracy was not good. So, we performed class rebalance to acheive a better accuracy on training and validation accuracy. And we have found a stable CNN model.
- Using the filter size of (5,5) has given a better CNN model as compared to filter of size (3,3) 


## Technologies Used
- Python 3.8.5



## Acknowledgements
- This Project is a part of Upgrad CNN assignment
- The github link to this project is git@github.com:seemasim/House-Price-Prediction.git


## Contact
Created by [@seemasim] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
# Melanoma Skin Cancer Detection
> Multi-class classification model using a custom CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- `Melanoma` is a type of cancer that can be deadly if not detected early. It accounts for `75%` of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- Build a multiclass classification model using a custom convolutional neural network in TensorFlow
- **Dataset**: The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
- The data set contains the following 9 diseases:
  - Actinic keratosis
  - Basal cell carcinoma
  - Dermatofibroma
  - Melanoma
  - Nevus
  - Seborrheic keratosis
  - Squamous cell carcinoma
  - Pigmented benign keratosis
  - Vascular lesion
  
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- There are 3 models building during the development process.Model 1 was trained for 20 epochs with available data.Model 2 was trained for 20 epochs with keras built-in data augmentation.Model 3 was trained for 30 epochs (1500 images) and (500 images)
- First model is a overfitting model where the accuracy & loss difference for training and validation data is significantly large
- Second model is build to handle the overfitting by introducing agumentation, but the model accuracy is low in comparison due to class imbalance
- Third model is build to handle class imbalance and observed the improvement in accuracy (training accuracy is `87.62%` & validation accuracy is `72.81%`)


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
 - Pandas - v1.1.3
 - Numpy - v1.22.3
 - Matplotlib - v3.3.2
 - TensorFlow - v2.8.0
 - Augmentor - v0.2.9

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by Upgrad CNN Assignment
- [Tensorflow image classification tutorial](https://www.tensorflow.org/tutorials/images/classification).
- [Tensorflow data augmentation tutorial](https://www.tensorflow.org/tutorials/images/data_augmentation).


## Contact
Created by [@trezajacob] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
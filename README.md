# Project Name
Melanoma Detection Assignment

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
- A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- To build a CNN based model which can accurately detect melanoma.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).
  - All images were sorted according to the classification taken with ISIC, and 
  - all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion


## Conclusions
- Conclusion 1: Initial multi-layer CNN model shows overfitting with high training accuracy and low validation accuracy
- Conclusion 2: Dropout to final layer and image augmentation is added to the model. This balances the validation and training accuracy somewhat, but there are clear signs of class imbalance
- Conclusion 3 Final model uses Augmentor library to generate augmented images for all classes. This results in more balanced model which is neither overfitting nor underfitting.


## Technologies Used
- tensorflow - 2.18.0
- numpy - version 2.0.1
- pandas - version 2.2.2
- seaborn - version 0.13.2


## Contact
Created by [@sjpathak] - feel free to contact me!

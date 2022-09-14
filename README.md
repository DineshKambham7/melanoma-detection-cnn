# Project Name
> Multi-class classification model using a custom CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- Build a multiclass classification model using a custom convolutional neural network in TensorFlow
- Dataset: The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
- The data set contains the following 9 diseases:
Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Seborrheic keratosis
Squamous cell carcinoma
Pigmented benign keratosis
Vascular lesion


## Conclusions
- There are 3 models building during the development process
- First model is a overfitting model where the training and validation accuracy & loss has significant gap.
- In the second model overfitting was handled with augmentation. But the gaps between training and validation accuracy is reduced. But there were signs of Class Imbalance
- In the third model the class imbalance is handled and the model has significantly improved accuracy.



## Technologies Used
Pandas - v1.1.3
Numpy - v1.22.3
Matplotlib - v3.3.2
TrnsorFlow - v2.8.0
PIL - v8.0.1
Augmentor - v0.2.9


## Acknowledgements
- Augmentor guide: https://augmentor.readthedocs.io/en/master/
- Keras: ttps://keras.io/guides/


## Contact
Created by [@DineshKambham7] - feel free to contact me!
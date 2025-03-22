# Skin-cancer
## Melanoma Detection Assignment

The Assignment is to make a multiclass classification model using convolutional neural network which can accurately detect melanoma, which is a type of cancer that can be deadly if not detected early and it accounts for 75% of skin cancer deaths.
[Download Data set here](https://drive.google.com/file/d/1xLfSQUGDl8ezNNbUkpuHOYvSpTyxVhCs/view?usp=sharing)

## Table of Contents

- General Information
- Conclusions
- Technologies Used

## General Information

Melanoma is a type of cancer which accounts for 75 percent of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. The model can classify nine different classes of the disease which includes 'actinic keratosis', 'basal cell carcinoma', 'dermatofibroma', 'melanoma', 'nevus', 'pigmented benign keratosis', 'seborrheic keratosis', 'squamous cell carcinoma', 'vascular lesion'.
Here in order to solve this problem we are using the International Skin Imaging Collaboration (ISIC) dataset which contains 2357 which are sorted according to the classification taken with ISIC
Conclusions

A combination of image augmentation, batch normalization and dropouts seem to be working well in reducing the overfitting of the data.
The training and validation loss is nearly decreasing with every epoch.
Technologies Used

- Tensorflow- 2.12.0
- Numpy- 1.22.4
- Augmentor- 0.2.12
- Keras – 2.12.0

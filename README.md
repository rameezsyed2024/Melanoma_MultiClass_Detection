# Melanoma-Detection-Assignment
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

In this assignment, we will build a multiclass classification model using a custom convolutional neural network in TensorFlow. 


## Table of Contents
* General Info
* Technologies Used
* Conclusions
* Acknowledgements



## General Information
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

You can download the dataset [here](https://drive.google.com/file/d/1xLfSQUGDl8ezNNbUkpuHOYvSpTyxVhCs/view).

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



## Technologies Used
- Python Libraries for visualising, training & Testing model. Such as - numpy, pandas , statsmodel, sklearn, seaborn & matplotlib.
- Jupyter Notebook
- Tensorflow
- Github



## Conclusions
1. Model 1:
   Around the 19th and 20th epochs, we can also notice differences in loss functions in training and validation data. This is a clear instance of overfitting, in      which the model learnt too much from the training dataset and is unable to perform well on the validation dataset.
   - Training Accuracy: 89.290
   - Validation Accuracy: 51.68
  
2. Model 2 with augmented data:
   Training accuracy has not increased when compared to the basic model, however the gap between training and validation accuracy has narrowed. In addition,           validation accuracy is marginally improved over the original model. The gap between training loss and validation loss is also narrowed. And we see that             overfitting has been decreased as a result of data augmentation.
   - Training Accuracy: 60.49
   - Validation Accuracy: 54.14
  
3. Final Model after rectifing class imbalance:
   Because to augmentation and class imbalance management, training and validation accuracy has enhanced dramatically. The model does not overfit. This model can      serve as the final model.
   - Training Accuracy: 95.44
   - Validation Accuracy: 79.96



## Acknowledgements
- Upgrade Learning
- Upgrade Faculty
- Rameez Syed


## Contact
Created by [Rameez Syed](https://github.com/rameezsyed2024/Melanoma_MultiClass_Detection) - feel free to contact me!
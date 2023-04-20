# Melanoma Detection Assignment
Problem statement

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

#### The data set contains the following diseases:

##### Actinic keratosis
##### Basal cell carcinoma
##### Dermatofibroma
##### Melanoma
##### Nevus
##### Pigmented benign keratosis
##### Seborrheic keratosis
##### Squamous cell carcinoma
##### Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Three models have been tried and the observations are here
### Model 1
The Training Accuracy and Validation Accuracy are more or less par in first few epochs from 30% to 50% and after that validation accuracy has an average of 50% but training accuracy consistently grew up to 80% on 20th Epoch. it clearly shows the OVERFITTING of the model.

The Training loss and Validation loss also shows the same pattern as the validation loss starts to increase after it came down to 1.3. But the training loss consistently decreased, this also clearly shows the pattern of OVERFITTING

### Model 2
After adding the Drop out Layer, Overfitting is greatly reduced as seen in the Training Accuracy vs Validation Accuracy graph.

But, the Validation Loss tend to increase when the number of epochs are increased, this tends to show there is still Overfitting present in the model

Also, the accuracy of this model is pretty low, as the validation accuracy is below 50%, we need to address the class imbalance for both Training Dataset and Validation Data set as well.

### Model 3

Overfitting and Underfitting are removed from the chart shown above.

Training Accuracy 89.97% and Validation Accuracy 87.94%. Tremendous progress has been made in this model.

Training Loss 27.85% and Validation loss 44.47%. Loss have been significantly decreased.

After addressing the Class Imbalance, overall model performance, increased significantly.

## We will use Model 3 for classification.


## Technologies Used
-Python
Google Colab
Github

# Melanoma-Detection-Assignment
> To build a CNN based model which can accurately detect melanoma.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)



## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
The data set contains the following diseases:

1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion


## Conclusions
- The class rebalance resulted in minimizing overfititng of the data. Consequently the loss is reduced.  However, the Acurracy was rendered significantly low.

- Using ImageDataGenerator has made the data to over fit at high ratio.

- Using both dropout and ImageDataGenerator minimized the overfit of the model.

- Finally, the Batch Normalization and Augumentation yeilded good results. 




## Technologies Used
- Numpy
- Pandas
- matplotlib
- tensorflow
- Keras




# Melanoma Detection Using CNN
In cancer, there are over 200 different forms. Out of 200, melanoma is the deadliest form of skin cancer. The diagnostic procedure for melanoma starts with clinical screening, followed by dermoscopic analysis and histopathological examination. 
Melanoma skin cancer is highly curable if it gets identified at the early stages. The first step of Melanoma skin cancer diagnosis is to conduct a visual examination of the skin's affected area. Dermatologists take the dermatoscopic images of the skin lesions by the high-speed camera, which have an accuracy of 65-80% in the melanoma diagnosis without any additional technical support. 
With further visual examination by cancer treatment specialists and dermatoscopic images, the overall prediction rate of melanoma diagnosis raised to 75-84% accuracy. 
The project aims to build an automated classification system based on image processing techniques to classify skin cancer using skin lesions images. 

## Table of Contents
* [General Info](#general-information)
* [Steps Followed](#steps-followed)

  ## General Information

We have to build a CNN based model which can accurately detect melanoma. 
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. 

The overarching goal is to support the efforts to reduce the death caused by skin cancer. The primary motivation that drives the project is to use the advanced image classification technology for the well-being of the people. Computer vision has made good progress in machine learning and deep learning that are scalable across domains. 

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images. 

The data set contains the following diseases: 
-  Actinic keratosis
-  Basal cell carcinoma
-  Dermatofibroma
-  Melanoma
-  Nevus
-  Pigmented benign keratosis
-  Seborrheic keratosis
-  Squamous cell carcinoma
-  Vascular lesion

  ## Steps Followed
-   CNN Model is built to classify disease label
-   Train folder is divided in to Training (80%) and Validation sets (20%) with Batch Size, Image height and Width are defined to create model
-   Initial Model is build using 3 Convolutional Layers, 3 Pooling areas, 1 Flatten layer and then Dense layers to extract output labels
-   Augmentation and dropout is performed to improve performance of model and handle Overfit
-   Class rebalance is performed using Augmentor to add more balance for the ones having less number of samples
-   With New data, Train+output folder data is divided in to Training (80%) and Validation sets (20%) with Batch Size, Image height and Width are defined to create model
-   Final model is build on new data along with Normalization to improve performance thereby handling underfit.

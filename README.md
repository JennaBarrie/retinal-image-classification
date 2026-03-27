# retinal-image-classification

Diabetic retinopathy classification using EfficientNet and MobileNet on the APTOS 2019 dataset

Internship Project with Northwestern University

## Overview

The goal is to compare the performance of **EfficientNet-B0** and **MobileNetV3-Small** on the [APTOS 2019 Blindness Detection Dataset](https://www.kaggle.com/c/aptos2019-blindness-detection). This project classifies retinal images based on the severity of diabetic retinopathy. 
The dataset used is the **APTOS 2019 Blindness Detection Dataset** from Kaggle. It contains high-resolution retinal images labeled with diagnosis severity, 0-4.  
Note: The dataset is not included in this repo. To run this code, download it from Kaggle and place the images in the folder specified by the `base_path` in the notebook.

## Models:
1. EfficientNet-B0 (pretrained, fine-tuned for 5 classes)  
2. MobileNetV3-Small (pretrained, fine-tuned for 5 classes)
    
## Results:
Validation Accuracy and Loss were tracked for 10 epochs.  
EfficientNet-B0 performed slightly better overall in terms of validation accuracy and stability.

## How to run: 
1. Clone the repo:
git clone https://github.com/JennaBarrie/retinal-image-classification.git
cd retinal-image-classification
2. Download the APTOS 2019 dataset from Kaggle and set the path in the notebook:
base_path = "/path/to/aptos2019-blindness-detection"
3. Run the notebook retinopathy_classification.ipynb.


# Diabetic classifciation and model optimization
The goal of this project is to build a high accuracy/real time model able to classify Diabetic degree. The model takes as an input an image and predicts its label. 
1. No DR
1. Mild DR
1. Moderate DR
1. Severe DR
1. Proliferate DR
# Getting Started
## Dataset
The Dataset contains 3662 training images and 1928 for testing.<br />
A CSV file containing the labels is also available.<br />
The Dataset can be downloaded here: https://www.kaggle.com/c/aptos2019-blindness-detection/data.<br />
## Code
To train the model I used transfer learning for Resnet50.<br />
The Resnet50_model.py trains the model and stores the results (accuracy and loss functions, confusion matrix ...).  
```bash
python Resnet50_model.py
```
## Results
![]()





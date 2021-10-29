<img src=https://upload.wikimedia.org/wikipedia/commons/7/7c/Kaggle_logo.png>


# Pneumonia 3-Class Classification
The code used for my submissions, winning the in-class <a href="https://www.kaggle.com/c/detect-pneumonia-fall-2021/leaderboard"> Kaggle competition</a>, can be found:
* <a href="https://colab.research.google.com/drive/1SscqutZjmk5CDowhF3I7bMF30KM7C1sD?usp=sharing">Google Colab</a>
* <a href="https://github.com/Ggkenios/Pneumonia_Classification/blob/main/Detect_Pneumonia.ipynb">GitHub</a> 

## Goal
The goal was to classify chest x-ray images into 3 classes:
* healthy
* bacterial pneumonia
* viral pneumonia 

## Dataset 
The training dataset consisted of 4672 images out of which:
* 1227 images belong to class 0
* 2238 images belong to class 1
* 1207 images belong to class 2 

## Sumbission
The submissions employed:
* Data augmentation
* Transfer learning with EfficientNet models, trained on ImageNet
* Softmax ensemble (Soft Voting) for final predictions

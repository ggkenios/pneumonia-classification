# Pneumonia 3-Class Classification
This is the code used for my submissions, winning the in-class <a href="https://www.kaggle.com/c/detect-pneumonia-fall-2021/leaderboard"> Kaggle competition</a>. <br>
Can be found:
* Google Colab: <a href="https://colab.research.google.com/drive/1SscqutZjmk5CDowhF3I7bMF30KM7C1sD?usp=sharing">Colab</a>
* GitHub: <a href="https://github.com/Ggkenios/Pneumonia_Classification/blob/main/Detect_Pneumonia.ipynb">GitHub</a> 

## The Goal
The goal was to classify 1168 chest x-ray images into 3 classes:

* no disease
* bacterial pneumonia
* viral pneumonia 

## The Dataset 
The training dataset consisted of 4672 images out of which:

* 1227 images belong to class 0
* 2238 images belong to class 1
* 1207 images belong to class 2 

## Submission
The submissions employed:
* Data augmentation
* Transfer learning with EfficientNet models, trained on ImageNet
* Softmax ensemble (Soft Voting) for final predictions

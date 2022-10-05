# Prediction-Of-Heart-Disease-Among-Older-People
This is a data mining project implemented in Python

Heart disease has become the leading cause of death for people in the United States. According to the American Heart and the National Institutes of Health, about 655,000 Americans die from heart disease each year—that is 1 in every 4 deaths (Source: https://www.cdc.gov). Therefore, diagnosis and prevention of heart disease has become an important research in the medical field. This project aims to provide the medical community with a model that detects the presence of heart disease. In this project, we aim to build a model to detect the presence of heart disease correctly by analyzing various features and applying data mining techniques. The response variable is a categorical variable with value 1 and 0; 1 means the patient suffers from heart disease, and 0 means the patient doesn’t suffer from heart disease. So, basically, we are dealing with a binary classification problem. In addition, we also want to find out which features have decisive influence in the final diagnosis. 

## Data Source 
The dataset is from https://www.kaggle.com/ronitf/heart-disease-uci 
Reference: https://www.ahajournals.org/doi/10.1161/CIR.0000000000000757 

## Data Mining Models Used
1) KNN
2) Logistic Regression

## Results
| Model  | Accuracy | Recall  | Precision | F1 Score |
| ------------- | ------------- |------------- | ------------- | ------------- | 
| KNN | 83.03% | 85.88% | 83.65% | 84.15% |
| Logistic Regression | 84.03% | 87.64% | 84.28% | 85.49% |


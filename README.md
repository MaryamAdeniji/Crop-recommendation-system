# Crop-recommendation-system
This project uses supervised and unsupervised Machine learning techniques to provide recommendations of crops using soil characteristics such as Nitrogen, Phosphorous, Potassium, pH value and weather conditions such as rainfall and humidity. The aim of this project is to show how data-driven methods can support agricultural food production. 

### Objectives

###### Build a predictive model capable of recommending optimal crops
###### Apply both classification (supervised) and clustering (unsupervised) approaches
###### Evaluate performance using industry‑standard metrics
###### Demonstrate end‑to‑end ML workflow using the industry standard practice for data mining CRISP‑DM.


### Methodology (CRISP‑DM)
1. Business Understanding:
   
Identify how machine learning can enhance crop selection and agricultural planning.

2. Data Understanding & Collection:

The dataset which includes 22 classes of various crops, soil characteristics such as Nitrogen, Phosphorous, Potassium, pH value and weather conditions such as rainfall and humidity was sourced from Kaggle.

3. Data Cleansing & Preparation:

The necessary libraries were imported and the data was loaded into the notebook. The shape and information of the data were checked to provide an understanding of its characteristics. Check for missing values was done using the .isnull().sum function in pandas, data had no missing values. Check for duplicates was also done using the .duplicated().sum() and no duplicates were found. Descriptive statistics was computed using .describe(). The target variable "Crop" was encoded using LabelEncoder() function. The data is partitioned into a training and test set.


4. Model Selection & Training

Supervised techniques used: Support Vector Machine (SVM), Multilayer Perceptron (MLP), Convolutional Neural Network (CNN). Unsupervised technique: Clustering to explore underlying data structure

5. Model Evaluation

Models evaluated using: Accuracy, Precision, Recall, F1‑Score. Hyperparameter tuning was performed using GridSearchCV to prevent overfitting and improve generalization.

6. Deployment

A fully reproducible .ipynb file is provided for demonstration.

### Results
SVM performed best with 99% accuracy, CNN and MLP have similar accuracy of 98.40%. From the above, we can conclude that application of the SVM will be more efficient in deploying a crop recommendation system


##### N.B.: This project was a part of my academic coursework/assessment at Nottingham Trent University and is only shared publicly for my portfolio purposes.

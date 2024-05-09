
# Malicious Website Detection


## Project Overview

The primary objective of this study was to develop an effective and reliable method for distinguishing between malicious and benign websites. By leveraging machine learning techniques, specifically exploratory data analysis (EDA) and regression analysis, we aimed to uncover patterns and characteristics that could accurately classify websites into their respective categories.
## Dataset

The study utilized a comprehensive dataset obtained from Kaggle, containing 1,781 instances and 20 features related to websites, such as URL characteristics, server information, content length, network traffic patterns, and DNS query times. The dataset was preprocessed, and missing values were handled using appropriate imputation techniques.

https://www.kaggle.com/datasets/xwolf12/malicious-and-benign-websites?resource=download
## Methodology

The project followed the following methodology:

1. Exploratory Data Analysis (EDA): Conducted an in-depth EDA to gain insights into the dataset, including calculating summary statistics, creating feature distributions, identifying outliers, and exploring potential correlations. The insights from this phase guided the subsequent data preprocessing and feature selection steps.

2. Data Preprocessing: Handled missing values using techniques such as K-Nearest Neighbors imputation, mode imputation, and mean imputation. Performed feature encoding and scaling as necessary.

3. Model Development: Employed regression analysis techniques, including Random Forest and ensemble models (Logistic Regression, Random Forest, and SVC), to build predictive models for classifying websites as malicious or benign.

4. Model Evaluation: Evaluated the performance of the models using metrics such as accuracy, precision, recall, and F1-score. Conducted cross-validation and analyzed the confusion matrix to assess the models' strengths and weaknesses.

5. Feature Importance Analysis: Investigated the most influential features contributing to the models' predictions, providing insights into the characteristics associated with malicious websites.
## Results

The Random Forest model achieved an overall accuracy of 96%, with high precision for both malicious and benign classes but relatively lower recall (71%) for the malicious class. The ensemble model, while achieving perfect precision for the malicious class, had lower recall (53%).

The study discussed the trade-offs between precision and recall, highlighting the importance of balancing these metrics based on the operational context and the costs associated with false positives and false negatives.

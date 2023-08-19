# MLOps Project - Stack Exchange Question Classification

![image](https://github.com/shivam-gupta0/MLOps-Project/assets/85798077/7dfe89ad-8417-4847-8610-8e794ae94b41)

# Overview <br>
This project focuses on the classification of questions from the Stack Exchange platform, specifically targeting those related to machine learning. The primary objective is to build a robust machine learning model that can identify machine learning-related questions from a pool of diverse topics.<br><br><br>

# Table of Contents<br>
Data Preparation<br>
Feature Engineering<br>
Model Training<br>
Model Evaluation<br>
Textual Features<br>
Conclusion<br>
<br><br>
# Data Preparation<br>
The project begins with data acquisition. We source our data from the Cross Validated Stack Exchange API and store it for analysis. The dataset includes various features such as question titles, question bodies, and creation dates, which we preprocess for effective machine learning.<br><br><br>

# Feature Engineering<br>
Feature engineering is a crucial step in the machine learning pipeline. We perform several data transformations to prepare our dataset for modeling. Notable steps include:<br>
<br>
Converting creation dates to a numerical format.<br>
Dropping irrelevant features such as 'FavoriteCount'.<br>
Calculating text lengths for 'Title' and 'Body'.<br>
Labeling questions as machine learning-related based on their 'Tags'.<br><br><br>
# Model Training<br>
For the initial model, we use logistic regression on the engineered numeric features. This allows us to assess the quality of our data preparation and feature engineering before incorporating textual features.<br><br><br>

# Model Evaluation<br>
To evaluate our models, we focus on metrics like precision-recall curves and ROC curves due to class imbalance. We also compare our results to baseline models, such as a classifier trained on raw data and a naive model.<br>

# Textual Features <br>
The next phase of the project involves leveraging textual features, including 'Title' and 'Body', for improved classification performance. We employ TF-IDF vectorization to convert text data into numerical features and train a logistic regression model on these features.<br><br><br>

# Conclusion <br>
In conclusion, this project demonstrates approach to tackle the problem of Stack Exchange question classification. We've showcased expertise in data preprocessing, feature engineering, model training, and evaluation. The use of both numeric and textual features highlights a well-rounded approach to solving real-world machine learning challenges. <br><br><br>

This README represents only a summary of the project. For a detailed walkthrough and access to the code, please refer to the project files.<br>

Made with passion by Shivam Gupta.

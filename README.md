# Customer Churn Prediction with MLOps <br>
**Overview** <br>
This project focuses on building a machine learning model to predict customer churn and demonstrates MLOps best practices. Customer churn prediction is a critical task for businesses, and this project showcases how to develop, deploy, and manage a churn prediction model efficiently.<br>

**Features** <br>
Jupyter Notebooks: The project is structured using Jupyter Notebooks for a clear and interactive development process.<br>

MLflow: MLflow is used for tracking experiments, packaging code into reproducible runs, and managing model versions. The project leverages MLflow to ensure model reproducibility and easy model management.<br>

PyCaret: PyCaret is a powerful library for automating machine learning workflows. It streamlines the model development process and enables easy model comparison and selection.<br>

**Project Structure** <br>
This repository contains the following notebooks:<br><br>

1. mlflow_churn_model_registration.ipynb<br>
This notebook demonstrates how to register a churn prediction model using MLflow. Key highlights include:<br>

Setting up MLflow tracking to log experiments and model versions.<br>
Using PyCaret to perform automated machine learning experiments.<br>
Selecting the best model and visualizing its performance.<br>
Saving the final model pipeline for deployment.<br><br>
2. churn_model_development.ipynb<br>
This notebook focuses on the development of the churn prediction model and its registration with MLflow. It includes:<br>

Setting up MLflow tracking.<br>
Data preprocessing and setup using PyCaret.<br>
Model training, selection, and evaluation.<br>
Saving the best model for deployment.<br><br>
**Usage**<br>
To run these notebooks, follow these steps:<br>

Install the required libraries by running pip install mlflow==2 pycaret.<br>

Set up the necessary environment variables, such as MLFLOW_TRACKING_USERNAME, MLFLOW_TRACKING_PASSWORD, and MLFLOW_TRACKING_URI.<br>

Run the notebooks in a Jupyter environment, such as Google Colab.<br>

**Conclusion**<br>
This project showcases best practices in MLOps, including experiment tracking, model selection, and deployment preparation. By following the steps outlined in the notebooks, you can learn how to develop and deploy a customer churn prediction model efficiently. The use of MLflow and PyCaret simplifies the process and ensures reproducibility, making it suitable for real-world machine learning projects.<br>

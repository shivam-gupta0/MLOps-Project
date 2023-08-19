# MLOps Project - Stack Exchange Question Classification

![image](https://github.com/shivam-gupta0/MLOps-Project/assets/85798077/7dfe89ad-8417-4847-8610-8e794ae94b41)

# Overview <br>
This MLOps project serves as an educational resource for understanding and implementing Machine Learning Operations (MLOps) principles and tools in the context of Stack Exchange question classification. It aims to guide learners through the process of building a machine learning solution while seamlessly integrating essential MLOps practices.<br><br><br>

# Table of Contents<br>
Data Preparation<br>
Feature Engineering<br>
Model Training<br>
Model Evaluation<br>
Textual Features<br>
Conclusion<br>
<br><br>
# Data Preparation<br>
**DVC (Data Version Control)** <br>
To ensure reproducibility and version control, we utilize DVC (Data Version Control) for managing our dataset. DVC allows us to: <br>

Version and store our dataset efficiently.<br>
Track changes and versions in a Git-like fashion.<br>
Collaborate with team members while maintaining data integrity.<br>
Ensure data traceability throughout the project.<br>
The dataset is sourced from the Cross Validated Stack Exchange API and stored using DVC. This approach ensures data consistency and traceability throughout the project.<br><br><br>

# Feature Engineering<br>
Robust feature engineering is fundamental to successful machine learning. We engineer our dataset, including numerical features and labels, while maintaining data lineage using DVC. Key feature engineering steps include: <br>

Conversion of creation dates to numerical format. <br>
Removal of irrelevant features like 'FavoriteCount'.<br>
Calculation of text lengths for 'Title' and 'Body'.<br>
Labeling questions as machine learning-related based on their 'Tags'.<br><br><br>
# Model Training<br>
Our MLOps approach extends to model training, facilitated by MLOps libraries like DVC. We manage model versions and experiment tracking using: <br>

**MLflow**<br>
MLflow allows us to:<br>

Track and manage experiments.<br>
Log parameters, metrics, and artifacts.<br>
Compare and reproduce experiments easily.<br>
Maintain a clear experiment history.<br>
An initial logistic regression model is trained on the engineered numeric features, making it easy to track model versions and performance.<br><br><br>

# Model Evaluation<br>
Model evaluation is conducted using DVC-tracked data and model versions. We emphasize precision-recall curves and ROC curves due to class imbalance. We also compare our model results to baseline models, enhancing the project's transparency.<br>

# Textual Features <br>
In the next phase, we harness the power of textual features, such as 'Title' and 'Body,' to further improve classification performance. We employ TF-IDF vectorization and train a logistic regression model on these features, all managed with DVC.<br><br><br>

# MLOps Integration
This project showcases a complete MLOps workflow, from data versioning with DVC to model versioning and experiment tracking. By integrating MLOps libraries like DVC and MLflow, we ensure: <br>

Reproducibility: Easily reproduce experiments and results.<br>
Collaboration: Collaborate with team members seamlessly.<br>
Model Versioning: Keep track of model versions and their performance.<br>
Experiment Tracking: Log and compare experiments for model improvement.<br>
Data Lineage: Trace data changes throughout the pipeline.<br><br><br>

# Conclusion <br>
In conclusion, this MLOps project takes a teaching-oriented approach, guiding learners through the process of implementing MLOps principles and tools in the context of Stack Exchange question classification. We've not only explained key concepts but have also demonstrated their practical application, emphasizing the seamless integration of MLOps practices, including DVC and MLflow. This integration ensures data and model version control, experiment tracking, and reproducibility.

This README represents a summary of the project's educational MLOps integration. For detailed code, data, and model versioning, please refer to the project files.<br>


Made with passion by Shivam Gupta.

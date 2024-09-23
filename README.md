# Mobile Price Range Prediction - Classification

This repository contains the code and documentation for a machine learning project aimed at predicting the price range of mobile phones based on key features. The mobile phone market is highly competitive, and identifying factors that impact pricing is vital for manufacturers, marketers, and consumers.

# Project Overview
The objective of this project is to develop a machine learning model capable of classifying mobile phones into one of four price ranges: low, medium, high, or very high. The dataset used includes approximately 21 features, such as battery power, Bluetooth connectivity, camera resolution, screen size, and more.

This project follows a well-defined workflow, from data preprocessing and exploratory analysis to model implementation and evaluation.

# Key Steps:
# Data Wrangling:
We ensure data consistency by addressing missing values and correcting anomalies. In particular, zero values in features like pixel resolution height and screen width are replaced with the mean of valid entries.

# Exploratory Data Analysis (EDA):
EDA provides crucial insights into the relationships between features and the price range. Through visualizations and summary statistics, we examine correlations, distributions, and trends that shed light on significant factors, including RAM, battery capacity, and camera quality.

# Hypothesis Testing:
Statistical hypothesis testing is used to validate assumptions and identify key drivers of mobile phone pricing. We handle outliers and confirm their potential impact on model accuracy and performance.

# Feature Engineering:
Feature engineering involves creating new variables or transforming existing ones to improve predictive power. Careful feature selection helps retain the most relevant information for classifying price ranges.

# Machine Learning Models:
Various machine learning algorithms, including logistic regression, random forest, and XGBoost, are implemented to build the classification model. We evaluate model performance using metrics such as accuracy, precision, recall, and F1-score. Hyperparameter tuning further enhances model effectiveness.

# Workflow
  # Data Collection
We use a dataset of mobile phones with 21 features that represent various hardware and software specifications.

  # Data Preprocessing

Handle missing or erroneous values.
Normalize or scale features if necessary.
Ensure data integrity by rectifying inconsistencies.
Exploratory Data Analysis (EDA)

  # Visualize distributions and relationships between features.
Conduct correlation analysis to identify important variables.
Understand data patterns and outliers.
Feature Engineering & Selection

  # Engineer meaningful features based on domain knowledge (e.g., creating a screen-to-body ratio feature).
Select relevant features using techniques such as feature importance from tree-based models.
Model Building

 # Experiment with multiple algorithms:
Logistic Regression
Random Forest
XGBoost
Optimize models by tuning hyperparameters using GridSearchCV or RandomizedSearchCV.
Model Evaluation

Assess model performance using metrics like accuracy, precision, recall, and F1-score.
Analyze confusion matrix to understand model predictions for each price range.
Compare performance across algorithms to choose the best-performing model.
# Conclusion
This project delivers valuable insights into how mobile phone features influence price range. We successfully developed a model that accurately predicts a phone's price category using critical features such as RAM, battery power, and pixel resolution. This information can be leveraged by businesses to understand market dynamics and make data-driven decisions.

# Key Findings:
RAM is the most significant factor influencing mobile phone prices.
Battery power and pixel resolution also play vital roles in determining pricing tiers.
The Random Forest model demonstrated the highest performance in predicting price range, followed by XGBoost.
# Future Work
Further fine-tuning of the models using additional hyperparameter optimization.
Incorporating more advanced techniques such as stacking or ensemble learning.
Expanding the dataset to include more diverse features, such as brand reputation or software capabilities.

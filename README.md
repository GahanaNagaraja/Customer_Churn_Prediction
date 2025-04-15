# Customer_Churn_Prediction

Customer churn prediction using PySpark MLlib to identify at-risk users through behavioral analytics and machine learning, enabling real-time retention strategies.
This project leverages PySpark and MLlib to predict customer churn based on telecom user data. It applies distributed computing to preprocess data, engineer features, and build scalable machine learning models that can predict whether a customer will churn, enabling data-driven retention strategies.

## Project Overview

Customer churn prediction is critical for businesses to identify and retain at-risk customers. This project processes telecom datasets using PySpark and applies machine learning algorithms to build and evaluate predictive models including:

- Naive Bayes

- Random Forest

- Gradient Boosted Trees


## Technologies Used

- PySpark & Spark MLlib

- Python

- Seaborn/Matplotlib (for visualization)


## Kaggle Datasets

- Public telecom churn datasets from Kaggle.

- Each row in the dataset represents a customer and contains information such as call minutes, plan types, customer service calls, and churn status.


## Modeling Process

- Data Preprocessing: Categorical to numerical conversion, feature selection
  
- Exploratory Data Analysis: Summary statistics, correlation analysis

- Model Training: Trained using MLlib on Spark clusters
  
- Model Selection: K-fold cross-validation to compare performance
  
- Evaluation Metrics: Accuracy, ROC-AUC, F1-score, Precision, Recall


## Evaluation Metrics
   

| Model                  | Accuracy | AUC  |
|------------------------|----------|------|
| Naive Bayes            | 53.67%   | 0.61 |
| Random Forest          | 88.91%   | 0.88 |
| Gradient Boosted Trees | 92.05%   | 0.86 |



## Key Findings

- Gradient Boosted Trees outperformed other models with 92.05% accuracy.

- Features like customer service calls and total day minutes had strong predictive power.

- PySpark’s scalability proved highly effective for handling large-scale data.


## Future Scope

- Real-time churn detection with streaming data.

- ETL pipeline using Apache Spark and PostgreSQL.

- Integration of external data sources (e.g., demographics, sentiment).

## Conclusion

This project showcases the use of PySpark and MLlib for predicting customer churn with high accuracy. Among the models tested, Gradient Boosted Trees performed best with 92.05% accuracy. The pipeline—from preprocessing to model evaluation—demonstrates how big data tools can drive actionable insights and support proactive customer retention strategies. This lays the groundwork for future enhancements like real-time predictions and production deployment.


## Authors

1. Gahana Nagaraja
   
2. Namratha Nagathihalli Anantha
   
3. Niharika Mysore Prakasha

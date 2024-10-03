# Employee-Retention-Prediction-Project
Project Overview
The Employee Retention Prediction Project aims to proactively identify employees at risk of leaving a company. This end-to-end data analysis solution leverages Google Cloud technologies to analyze key factors influencing employee retention and provide actionable insights for human resources.

Table of Contents
Technologies Used
Project Components
Data Analysis Workflow
Dashboard Overview
Key Insights
Future Improvements
License
Technologies Used
Google Cloud BigQuery: Database management and storage.
Python (Colab): Data processing and model building.
PyCaret: Machine learning library for churn prediction.
Looker Studio: Dashboard creation and data visualization.
Project Components
Database Creation: Set up a database in BigQuery to store employee data.
Data Connection: Used Python in Colab to connect to the BigQuery database for data extraction.
Churn Model Development: Built a churn prediction model using PyCaret, focusing on factors such as job satisfaction and tenure.
Data Export: Exported processed data back to BigQuery for further analysis.
Dashboard Creation: Developed a dashboard in Looker Studio to visualize employee churn metrics and insights.
Data Analysis Workflow
Data Collection: Gathered historical employee data, including job satisfaction, tenure, project count, and performance evaluations.
Data Preprocessing: Cleaned and transformed data for analysis.
Model Training: Trained a Random Forest model to predict employee churn based on various features.
Model Evaluation: Assessed model accuracy and performance.
Visualization: Created a dashboard to present key findings and metrics.
Dashboard Overview
The Looker Studio dashboard displays:

Churn Rates: Overall and department-specific churn percentages.
Employee Satisfaction Levels: Metrics indicating employee satisfaction.
Predicted Turnover: Identification of at-risk employees.
Key Performance Indicators: Metrics such as average tenure, last evaluation scores, and project counts.
Key Insights
Job Satisfaction: The most significant factor influencing employee retention.
Churn Prediction: The model achieved an 85% accuracy rate in predicting employee churn.
Departmental Analysis: Identified departments with the highest turnover rates, aiding targeted retention strategies.
Future Improvements
Data Enrichment: Incorporate additional data sources for enhanced predictions.
Model Optimization: Experiment with other machine learning algorithms to improve prediction accuracy.
Real-Time Analysis: Implement real-time data processing for ongoing churn monitoring.

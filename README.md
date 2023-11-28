# Using machine learning to predict the risk of sleep disorders based on individuals' lifestyle and health conditions

Group Members: Youxia Zhao, Peter Tran

Background: In the modern era, increasing pressures have led to a growing prevalence of sleep-related issues such as reduced sleep quality, disruptions in sleep patterns, and diagnosable sleep disorders. These challenges are particularly prevalent among, resulting in a significant impact on their overall quality of life and health. 

Objective: Our project aims to develop a machine learning model that utilizes individual lifestyle information and health condition data to predict the risk of sleep disorders. Our primary objectives encompass: 1) Identify potential risk factors for sleep disorders, enabling individuals to take preventative measures. 2) Provide healthcare professionals with a tool to identify individuals at risk of sleep disorders at an earlier stage.
 
Dataset: We will utilize data extracted from the National Health and Nutrition Examination Survey (NHANES) for the years 2015-2016 and 2017-2018[1]. The dataset will undergo rigorous data preprocessing, not limited to handling of missing values and employing kernel density estimation to improve the learning potential of the model. After that, we anticipate working with a dataset containing approximately 6000 patient records. The chosen input features include 1) dietary habits, 2) physical activity, 3) smoking status, 4) alcohol consumption, 5) BMI (Body Mass Index), 6) chronic diseases. To facilitate analysis, categorical features will be transformed into numerical values, and data standardization will be performed. The class labels will represent a binary classification of patients: 0 - Non-cases and 1 - Cases.
 
Methods: Drawing from prior research[2][3] which primarily investigated associations between sleep disorders and specific features, our study aims to extend the understanding of this field. We will utilize Logistic Regression as a baseline model, and its capacity to capture intricate patterns will be augmented by introducing basis functions. Subsequently, L2 regularization will be applied to optimize the model's performance and we will analyze how the feature weights change as the regularizer strength increases. Then we will explore the efficacy of Support Vector Machine (SVM) models and Random Forest Classifier (RFC). A comparative analysis will be conducted on the results generated by the three models, evaluating their respective performances. Through this comprehensive approach, we seek to identify the most effective model for predicting sleep disorders, contributing to the advancement of sleep disorder diagnosis and treatment.

Results: The study findings will be presented in a tabular format, providing essential metrics including 1) Confusion Matrices, 2) Accuracy, Precision, Recall, 3) Area Under the Receiver Operating Characteristic Curve (AUC-ROC), and 4) Area Under the Precision-Recall Curve (AUC-PR).


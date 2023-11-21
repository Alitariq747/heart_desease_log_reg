# heart_desease_log_reg

Heart Disease Prediction with Logistic Regression
Overview

This project aims to predict the likelihood of heart disease in individuals based on various health measures such as age, blood pressure, hypertension, smoking, diabetes, and gender. Logistic regression, a common classification algorithm, was employed for the predictive modeling.

Dataset
The dataset used in this study was sourced from Kaggle and contains comprehensive information about individuals' health status and associated risk factors.

Features
Age
Blood Pressure
Hypertension
Smoking
Diabetes
Gender
Target
Presence or absence of heart disease
Methodology
Logistic Regression Model
A logistic regression model was chosen for its simplicity and interpretability. The coefficients of the model were analyzed to understand the impact of each health measure on the likelihood of heart disease.

Results and Insights
The study revealed the following key insights:

Hypertension and Diabetes: Individuals with hypertension and diabetes are significantly more likely to develop heart-related diseases.

Age and Smoking: Age and smoking were identified as additional risk factors, with higher age and smoking habits increasing the likelihood of heart disease.

Gender: Surprisingly, being male was found to be associated with a significant increase in the chances of heart-related illnesses.

Model Evaluation
The model's accuracy was assessed using the classification report from scikit-learn. The results indicate a promising accuracy, but it is essential to consider other metrics such as precision, recall, and F1 score, especially in imbalanced datasets.

How to Use
To explore the project and replicate the analysis:

Clone this repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/heart-disease-prediction.git
Set up your Python environment with the required dependencies:

bash
Copy code
pip install -r requirements.txt
Open the Jupyter notebook (heart_disease_prediction.ipynb) to view the analysis and results.

Next Steps
This project lays the foundation for further exploration and refinement of the model. Potential future steps include feature engineering, hyperparameter tuning, and the exploration of more advanced machine learning algorithms.

Feel free to reach out if you have any questions or suggestions!







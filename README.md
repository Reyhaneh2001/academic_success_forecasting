# **Student Grade Prediction using Machine Learning**

## **Project Overview**
This project aims to predict students' final grades (G3) based on various features such as personal attributes, family background, study habits, and previous academic performance. Using machine learning techniques, including **XGBoost Regressor** and **Deep Learning**, the goal is to build a robust model that accurately forecasts student grades.

### **Objective**
The objective of this project is to develop a predictive model that estimates the final grade (G3) of a student based on various features, such as:
- Personal and family background (e.g., parental education, family size)
- Study habits (e.g., study time, failures)
- School-related factors (e.g., school type, internet access)
- Health and social aspects (e.g., health status, freetime)

### **Techniques Used**
- **XGBoost Regressor**: A powerful and efficient gradient boosting algorithm for regression tasks.
- **Deep Neural Networks**: A neural network architecture to capture complex non-linear relationships in the data.
- **Feature Scaling**: Standardization of features using `StandardScaler` for optimal model performance.
- **Cross-validation**: Used for model evaluation and ensuring the generalizability of the results.
- **Visualization**: Various charts and plots to visualize data, feature importance, and model performance.

## **Dataset**
The dataset used in this project consists of data collected from a Portuguese secondary school. It includes various attributes such as:
- **School**: The school attended (GP or MS).
- **Sex**: Gender of the student.
- **Age**: Age of the student.
- **Address**: Type of address (urban or rural).
- **Parental Information**: Parents' education levels, job, and family relationship quality.
- **Study and Social Habits**: Study time, failures, health status, etc.
- **Final Grades**: The target variable, which is the final grade of the student (G3).

### **Data Preprocessing**
- **Encoding Categorical Variables**: One-hot encoding was used for categorical variables like `school`, `sex`, `address`, etc.
- **Feature Scaling**: The features were standardized using `StandardScaler` to improve model performance.
- **Train-Test Split**: The data was split into training and testing sets (80% train, 20% test).

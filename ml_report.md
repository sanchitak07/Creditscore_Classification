# Machine Learning (316316)
## Credit Score Classification System

---

## 1. Introduction

Machine Learning (ML) is widely used in modern industries such as healthcare, finance, and business to analyze data and make intelligent predictions. In the financial sector, ML helps in evaluating customer creditworthiness through credit score classification.

A real-world ML application requires more than just building a model. It includes important stages like data preprocessing, model training, evaluation, deployment, and continuous monitoring.

This project develops a **Credit Score Classification System** that integrates all these stages into a complete and automated ML pipeline, making it suitable for real-world financial applications.

---

## 2. Objectives

The main objective of this project is to develop an end-to-end Machine Learning pipeline for a Credit Score Classification System.

### Specific Objectives:

- To understand the concept of an end-to-end ML pipeline  
- To perform data preprocessing and feature engineering  
- To train and evaluate different classification models  
- To build a scalable ML pipeline using Python libraries  
- To deploy the trained model using a web-based interface  

---

## 3. Software Requirements

### Programming Language & Platform

- **Python 3.x** – Used to develop the machine learning model and pipeline  
- **Google Colab** – Used for coding, training, and testing the model  

### Libraries Used

- **Pandas** – For data cleaning and analysis  
- **NumPy** – For numerical operations  
- **Scikit-learn** – For model training and evaluation  
- **Matplotlib & Seaborn** – For data visualization  

### Deployment Tool

- **Streamlit** – Used to build a web-based interface for real-time credit score prediction  

---

## 4. Scope of the Project

The scope of this project is to develop a real-world Credit Score Classification System using Machine Learning.

- Credit Dataset Analysis and Preprocessing  
- Credit Score Model Training  
- End-to-End ML Pipeline Creation  
- Web-Based Deployment Using Streamlit  
- User Input and Prediction System  

This project demonstrates how machine learning can be practically implemented in the financial sector for credit risk assessment.

---

## 5. Methodology

### Step 1: Data Collection

- Dataset collected from Kaggle  
- Dataset loaded from CSV file  
- Initial inspection using Pandas  

### Step 2: Data Preprocessing

- Handling missing values  
- Encoding categorical features  
- Feature scaling  
- Outlier removal  

### Step 3: Model Building

- Algorithm selection (Logistic Regression, Decision Tree, Random Forest)  
- Train-test split  
- Model training  

### Step 4: Model Evaluation

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

### Step 5: Pipeline Creation

- Scikit-learn Pipeline  
- Integrated preprocessing and model workflow  

### Step 6: Deployment

- Streamlit deployment  
- User interface design  
- Prediction result display  

---

## 6. Results
### 🔹 Deployed Web Application Interface

![Credit Score Classification System Home Page](image/home_page.png)

The above figure shows the deployed Streamlit web application interface.
It displays the system title, accuracy information, and real-time processing capability.
Users can click on "Get Started" to enter financial details and receive credit score predictions.

#### 🔹 Sample Dataset (First 10 Rows)
![Credit Score Classification System Home Page](image/dataset.png)


The above figure shows the first 10 rows of the credit score dataset.
It includes features such as Age, Gender, Income, Education, Marital Status, Number of Children, Home Ownership, and Credit Score category.

This initial inspection helps in understanding the dataset structure, feature types, and target variable before preprocessing and model training.

### 🔹 Model Training Interface
![Credit Score Classification System Home Page](image/train.png)

The above figure shows the model training interface of the deployed Streamlit application.

It allows the user to:
- Upload or select the dataset
- Choose the target column
- Configure the train-test split
- Start model training

The training summary panel displays dataset status, selected algorithm, and test split percentage.  
This interface makes the system interactive and user-friendly.

### 🔹 Model Performance Comparison
![Credit Score Classification System Home Page](image/model.png)

The above figure shows the performance comparison between Logistic Regression and Random Forest models.

Logistic Regression achieved:
- Accuracy: 93.94%
- Precision: 94.07%
- Recall: 93.94%
- F1 Score: 93.80%

Random Forest achieved:
- Accuracy: 96.97%
- Precision: 97.10%
- Recall: 96.97%
- F1 Score: 96.83%

From the comparison, Random Forest performed better and was selected as the final model for deployment.

The trained model successfully classifies customers into credit categories such as **Good, Standard, and Poor** based on financial details. The deployed web application provides real-time prediction results with satisfactory accuracy and performance metrics.

---

## 7. Advantages

- Improves Credit Risk Assessment  
- Saves Time and Manual Effort  
- Real-Time Prediction System  
- Reusable and Scalable Pipeline  
- Industry-Oriented Implementation  

---

## 8. Limitations

- Limited Dataset Size  
- Dependency on Data Quality  
- Risk of Model Bias  
- Requires Technical Maintenance  

---

## 9. Applications

- Banking and Financial Institutions  
- Credit Risk Assessment  
- Loan Approval Systems  
- Digital Lending Platforms  
- Financial Analytics Systems  

---

## 10. Conclusion

This project successfully demonstrates the development of a real-world Credit Score Classification System using an end-to-end machine learning pipeline.

It covers data collection, preprocessing, model training, evaluation, pipeline creation, and deployment. The system provides real-time credit score classification and reflects industry-oriented ML implementation.

Overall, this project bridges the gap between theoretical machine learning concepts and practical financial applications.

---

## References

- https://scikit-learn.org/stable/index.html  
- https://www.kaggle.com/  
- https://seaborn.pydata.org/  
- https://pandas.pydata.org/docs/  
- https://numpy.org/doc/  
- https://matplotlib.org/stable/users/index.html  

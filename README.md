# Healthcare-Analytics-for-Disease-Prediction-Project

**Title:** Liver Disease Prediction using Machine Learning on Cirrhosis Dataset

**Description:** The Liver Cirrhosis Detection project aims to develop a computational model or system to aid in the early detection of liver cirrhosis, a chronic liver disease characterized by scarring of the liver tissue. This project typically involves analyzing medical data such as liver function tests, imaging studies (e.g., ultrasound, MRI), and patient demographics to identify patterns and indicators associated with the presence or progression of cirrhosis. Machine learning algorithms or statistical methods may be employed to train the detection model, which could then be integrated into clinical workflows to assist healthcare professionals in diagnosing and monitoring liver cirrhosis more effectively. The ultimate goal is to improve patient outcomes through earlier detection and intervention, potentially reducing the morbidity and mortality associated with advanced liver disease.


**Features:** 
1. Cirrhosis Dataset Analysis: 
    The dataset is loaded, cleaned, and preprocessed to remove missing or irrelevant values.

2. Data Preprocessing Techniques: 
    Encoding categorical variables
    Handling class imbalance using SMOTE
    Feature scaling using StandardScaler

3. Multiple Classifier Models Used: 
    This project uses the following models: Logistic Regression
                                            Decision Tree
                                            Random Forest
                                            XGBoost
                                            LightGBM
                                            CatBoost
                                            SVM
                                            KNN
                                            Naive Bayes

4. Model Tuning & Evaluation: 
    Cross-validation with RepeatedStratifiedKFold
    GridSearchCV for hyperparameter tuning
    Evaluation with metrics like Accuracy, Confusion Matrix, Classification Report

5. Visualization & EDA: 
    Correlation heatmap
    Class distribution plots
    Feature importance visualizations

6. Model Saving: 
    Models are saved using joblib for future use.


**Tech Stack Used:**
1.Programming: Python       
2.Data Handling: pandas, numpy    
3.Visualization: matplotlib, seaborn    
4.ML Models: scikit-learn, xgboost, lightgbm, catboost    
5.Model Tuning:	GridSearchCV, cross_val_score, RepeatedStratifiedKFold    
6.Imbalanced Data: SMOTE from imblearn    
7.Evaluation: confusion_matrix, classification_report, ConfusionMatrixDisplay    
8.Model Saving: joblib


**Output:** ![LCP1](https://github.com/user-attachments/assets/0b33cc7f-6ec8-48e8-a1fc-97f29a8c69b2)
            ![LCP2](https://github.com/user-attachments/assets/3628c7bf-84e9-40fa-968d-e59cd02a80e0)
            ![LCP3](https://github.com/user-attachments/assets/b78cec8b-6705-4218-bf1c-5a6c0accdcb5)
            ![LCP4](https://github.com/user-attachments/assets/af3b27ce-d419-4edf-aa38-ae041de3255a)



            

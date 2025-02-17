# **Smoking Prediction using Machine Learning**

## **Project Overview**
This study aims to create a **predictive model** that can differentiate between **smokers and non-smokers** using a variety of **health-related factors**. Smoking is a major **risk factor** for several health conditions, and the ability to accurately classify individuals based on their health metrics has **significant implications** for **targeted healthcare initiatives and policy-making**.

## **Dataset**
The dataset used for this project is publicly available on **Kaggle** and contains **various health indicators** such as:
- **Blood pressure levels**
- **Cholesterol levels**
- **Hearing capacity**
- **General medical history**
- **Lifestyle factors**  
It is used to train different machine learning models to classify individuals as **smokers or non-smokers**.

🔗 **Dataset Source:** [Available on Kaggle](https://www.kaggle.com/) *(Replace with actual link)*

---

## **Machine Learning Pipeline**
The dataset was processed and analyzed through the following pipeline:

1. **Data Preprocessing & Principal Component Analysis (PCA)**  
   - Handling missing values
   - Normalizing features
   - Dimensionality reduction using PCA

2. **Splitting the Dataset**  
   - **70% Training Data**, **30% Testing Data**

3. **Model Training & Evaluation**  
   The following machine learning models were implemented and compared:
   - **AdaBoost Classifier**
   - **Support Vector Machine (SVM)**
   - **Random Forest Classifier**
   - **Gradient Boosting Classifier**
   - **Neural Network Classifier**
   - **Hard Voting Ensemble (Combining multiple models)**

4. **Comparison of Model Performance Metrics**  
   - **Accuracy**
   - **Precision**
   - **Recall**
   - **F1-Score**

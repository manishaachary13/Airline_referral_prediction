
# **Airline Passenger Referral Prediction**

## **📌 Project Overview**
This project aims to predict whether an airline passenger will likely refer to the airline based on various service-related factors. We provide insights to improve customer satisfaction and loyalty by analyzing customer feedback and service quality metrics.

## **🎯 Business Objectives**
- Identify key factors influencing passenger referrals.
- Understand patterns in customer reviews.
- Improve airline service quality and customer retention.
- Provide data-driven recommendations for enhancing customer experience.

## **📂 Dataset Description**
The dataset contains:
- **Numerical Ratings:** Seat Comfort, Food & Beverage, In-flight Entertainment, Staff Service, Value for Money.
- **Categorical Variables:** Gender, Travel Type (Business/Leisure), Airline Class (Economy/Premium/Business).
- **Textual Reviews:** Customer-written feedback (if available).

## **🛠️ Data Preprocessing**
- Handled missing values using mean/median/mode imputation.
- Encoded categorical variables using One-Hot and Label Encoding.
- Standardized numerical features using Min-Max Scaling.
- Split dataset into **80% training** and **20% testing**.

## **🤖 Machine Learning Models Implemented**
### **1. Logistic Regression**
- A baseline model for predicting customer referrals.

### **2. Random Forest Classifier**
- An ensemble method to improve accuracy by reducing variance.

### **3. Random Forest with Hyperparameter Tuning**
- Optimized with GridSearchCV for better performance.

### **4. Support Vector Machine (SVM) Classifier**
- Used RBF Kernel for better decision boundary separation.

### **5. SVM with Hyperparameter Tuning**
- Optimized regularization (C) and kernel type.

## **📊 Model Evaluation Metrics**
- **Confusion Matrix** to analyze prediction performance.
- **Accuracy, Precision, Recall, and F1-Score** to measure classification effectiveness.
- **ROC Curve & AUC Score** to evaluate model discrimination ability.

## **📈 Key Insights & Business Recommendations**
### 🔹 Key Factors Influencing Referrals
- **Seat Comfort & Staff Friendliness** highly impact customer referrals.
- **Food & Beverage Quality** is a major pain point in negative reviews.

### 🔹 Trends in Reviews
- **Recent reviews are more critical** of airline services compared to older ones.
- **Frequent flyers are more likely to refer** the airline.

### 🔹 Actionable Steps
- Improve **seat comfort and in-flight entertainment**.
- Train staff for **better customer interaction**.
- Enhance **food quality** to address negative feedback.

## **🚀 Future Enhancements**
- Use **Deep Learning (LSTMs/Transformers)** for sentiment analysis on textual reviews.
- Integrate **real-time social media sentiment tracking**.
- Expand the dataset with more airlines for a **comparative analysis**.
- Implement **Bayesian Optimization** for automated hyperparameter tuning.

## **📌 Conclusion**
This project effectively predicts airline passenger referrals using machine learning techniques. The findings provide valuable insights for airlines to enhance customer experiences and drive loyalty.

## **💡 Repository Structure**
```
├── data/                 # Dataset and processed data files
├── notebooks/            # Jupyter notebooks for data analysis & modeling
├── src/                  # Python scripts for preprocessing and model training
├── results/              # Model evaluation results
└── README.md             # Project documentation
```

## **🔗 Connect with Me**
If you have any questions or suggestions, feel free to reach out!

📩 Email: manisha.achary13@gmail.com  
💼 LinkedIn: https://www.linkedin.com/in/r-manisha-achary-470798204
📂 GitHub: https://github.com/manishaachary13


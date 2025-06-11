# **Customer Churn Prediction – Random Forest Classifier**

* **Overview**
  
  Built a machine learning model to predict whether a telecom customer will churn using a Random Forest Classifier. The model helps identify at-risk customers so the company can act early to retain them.

* **Steps Followed**
  
  1. Cleaned and preprocessed the dataset (handled missing values, label encoding, etc.)

  2. Performed EDA to uncover churn patterns

  3. Trained a Random Forest model (initial accuracy ~78%)

  4. Tuned hyperparameters using RandomizedSearchCV

  5. Final model achieved ~79.3% accuracy

* **Key Insights**
  
  1. Month-to-month contracts have the highest churn — suggest longer-term incentives.

  2. Fiber optic users churn more — review service experience or pricing.

  3. High monthly charges → high churn risk — offer loyalty or tenure-based rewards.

  4. Paperless billing & lack of support services → more likely to leave — bundle or upsell support.

* **Tools Used**

   Python, Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib

* **Model:**
  
    RandomForestClassifier

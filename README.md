# Customer-Churn-Analysis-and-Prediction

This project aims to predict whether a customer will churn (leave a company) using machine learning techniques. The pipeline includes data preparation, feature selection, model training, and evaluation. This is especially useful for subscription-based businesses to improve customer retention.

Task 1: Data Preparation
Notebook: task1.ipynb  
Description : Load and preprocess the dataset, handle missing values, and encode categorical variables.
- Data cleaning & preprocessing  
- Handling missing values  
- Categorical encoding (Label Encoding, One-Hot Encoding)

Task 2: Split Data for Training and Testing
Notebook : task2.ipynb  
Description : Split the dataset into training (80%) and testing (20%) sets.
- Understanding data splits  
- Use of train_test_split() function from sklearn

 Task 3: Feature Selection
Notebook : task3_feature_selection.ipynb
Description : Select important features like contract type, monthly charges, tenure, etc., for churn prediction.
- Correlation analysis  
- Domain knowledge integration  
- Feature importance techniques

Task 4: Model Selection
Notebook : task4_model_selection.ipynb 
Description : Select appropriate classification algorithms such as Logistic Regression, Decision Tree, Random Forest, or Gradient Boosting.
- Knowledge of classification algorithms  
- Model comparison and selection

Task 5: Model Training
Notebook : task5_model_training.ipynb
Description : Train the chosen model using the selected features and training dataset.
- Model training with `sklearn`  
- Pipeline setup  
- Feature-target mapping

Task 6: Model Evaluation
Notebook : task6_model_evaluation.ipynb
Description : Evaluate the model using accuracy, precision, recall, F1-score, and ROC-AUC.
- Evaluation metrics understanding  
- Confusion matrix, classification report  
- ROC Curve plotting

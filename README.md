# customer-churn-prediction
Machine Learning project to predict customer churn in subscription-based services using customer demographics, billing, internet, and streaming details. Built with Python, Pandas, and Scikit-learn using data preprocessing and Logistic Regression.  **Domain:** Customer Analytics / Subscription Services
## Project Overview
This project uses Machine Learning to predict customer churn in subscription-based services using customer demographics, subscription details, billing information, internet services, and streaming preferences.

### Technologies Used
- Python
- Pandas
- Scikit-learn
- Jupyter Notebook / Google Colab

### Methodology
The project involves data inspection, missing-value handling, categorical encoding, feature scaling, and model training. Numerical missing values are filled using median imputation, while categorical missing values are handled using the most frequent value. `OneHotEncoder` converts categorical data into numerical features, and `StandardScaler` scales numerical features.

### Pipeline Implementation
Scikit-learn's `Pipeline` and `ColumnTransformer` are used to combine preprocessing and model training into a single workflow. This keeps transformations organized and consistent during training and prediction. Fitting the pipeline on training data helps prevent data leakage from the test set.

### Why Logistic Regression?
Logistic Regression was selected as the baseline model because it is simple, computationally efficient, and suitable for binary classification. It predicts whether a customer is likely to churn (1) or stay (0). Compared with Decision Tree and Random Forest, it provides a straightforward starting point for understanding the problem and establishing baseline performance. However, these models would need to be compared experimentally to determine which performs best.

### Model Evaluation
- **Accuracy Score:** Measures the overall proportion of correct predictions.
- **Confusion Matrix:** Shows correct and incorrect predictions for churn and non-churn customers.

### Objective
The objective is to identify potential customer churn risks and explore how customer data can support better customer retention decisions.

**Domain:** Customer Analytics / Subscription Services

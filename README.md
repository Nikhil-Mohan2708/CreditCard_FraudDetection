# DataScience_Project - Credit Card Fraud Detection
# Purpose
This project aims to develop a machine-learning model to detect fraudulent credit card transactions. The detection of fraudulent activities in credit card transactions is crucial for financial institutions to prevent financial losses and protect their customers.
# Problem Statement
A credit card is one of the most used financial products to make online purchases and payments. Though Credit cards can be a convenient way to manage your finances, they can also be risky. Credit card fraud is the unauthorized use of someone else's credit card or credit card information to make purchases or withdraw cash.
Credit card companies must be able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase. 
The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
We have to build a classification model to predict whether a transaction is fraudulent or not.
# Data Sources
The dataset used for this project is the "(https://rb.gy/2d7ya1))". It contains transactions made by credit cards in September 2013 by European cardholders. The dataset is highly imbalanced, with only 0.172% of transactions labelled as fraudulent.
# Methodology
1. Data Exploration and Preprocessing: Explore the dataset, check for missing values, visualize class distributions, and handle imbalanced data using both under-sampling and over-sampling techniques. Perform feature engineering, including normalization and dimensionality reduction using Principal Component Analysis (PCA).

2. Model Training and Evaluation: Train multiple classification models, including Logistic Regression, Decision Tree, and Random Forest. Utilize hyperparameter tuning with randomized search and evaluate model performance using various metrics such as accuracy, precision, recall, F1-score, ROC-AUC, and confusion matrix.

3. Insights and Recommendations: Analyze feature importance, provide insights into model performance, and recommend the most effective model for fraud detection.
# Dependencies
1. Python 3.x

2. Pandas

3. NumPy

4. Scikit-learn

5. Seaborn

6. Matplotlib

7. Imbalanced-learn (for handling imbalanced data)

8. Jupyter Notebook or Google Colab (for running the analysis)
# Setup and Usage
1. Clone the repository to your local machine:

https://github.com/Nikhil-Mohan2708/CreditCard_FraudDetection.git

2. Install the required dependencies:

pip install -r requirements.txt

3. Run the Jupyter Notebook CreditCard_FraudDetection.ipynb to execute the data preprocessing, model training, and evaluation steps.

4. Follow the instructions within the notebook to understand the analysis and results.
# Additional Notes
Feel free to customize the analysis, explore different models, or incorporate additional features to improve model performance.

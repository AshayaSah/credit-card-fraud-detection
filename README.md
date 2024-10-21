# Credit Card Fraud Detection

## Project Overview
This project aims to develop a credit card fraud detection system utilizing machine learning techniques. By analyzing a dataset of financial transactions, we aim to classify transactions as fraudulent or non-fraudulent, thereby improving security in financial transactions.

## Dataset
The dataset used in this project contains anonymized credit card transactions. Each entry includes various features, such as transaction amount and multiple anonymized features (V1, V2, ..., V28) that represent different transaction characteristics. The target variable is 'Class', where 1 indicates a fraudulent transaction and 0 indicates a non-fraudulent transaction.

## Technologies Used
- **Python 3.x**
- **Libraries:**
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn

## Models
The following machine learning models were implemented:
- **Random Forest Classifier**
- **Decision Tree Classifier**
- **Support Vector Classifier (SVC)**

Each model was trained and evaluated based on its ability to classify transactions correctly.

## Results
The models achieved the following accuracy:
- **Random Forest Accuracy:** 99.92%
- **Decision Tree Accuracy:** 99.88%
- **SVC Accuracy:** 99.92%

These results indicate a high level of effectiveness in detecting fraudulent transactions.

## Visualizations
The project includes visualizations to better understand the data:
- **Feature Importance:** Visual representation of the importance of different features in the Random Forest model.
- **Correlation Matrix Heatmap:** Displaying the correlation between features and the target variable.
- **Class Distribution:** Count plot showing the distribution of fraudulent vs. non-fraudulent transactions.

## File I/O
The project saves predictions and classification reports to CSV and text files for future reference:
- Predictions are saved in **credit_card_fraud_predictions.csv**.
- Model evaluation reports are saved in **model_evaluation_report.txt**.

## Contributions
This project was developed as part of an academic assignment focusing on data manipulation, machine learning, and data visualization. Contributions and feedback are welcome.

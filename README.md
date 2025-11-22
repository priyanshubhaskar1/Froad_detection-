**Fraud Detection Using Machine Learning**

This project focuses on detecting fraudulent transactions using multiple machine learning models. It includes complete steps from data preprocessing to model evaluation, providing a practical and educational example of fraud analytics.

📝 **Project Description**

This project focuses on building a Fraud Detection System using Machine Learning by analyzing transactional data and identifying patterns associated with fraudulent activities. The dataset used in this project contains fictitious, non-real financial data created purely for educational and testing purposes. It does not represent real-world individuals or actual financial transactions.
The purpose of creating this dataset is to provide a safe and realistic environment for developing, training, and evaluating fraud detection algorithms without relying on sensitive or private real-world data. This allows students, researchers, and practitioners to explore data preprocessing, feature engineering, and machine learning model development responsibly.
Multiple machine learning models — including Random Forest, Logistic Regression, K-Nearest Neighbors, and Decision Trees — are trained and compared to identify the most effective approach for fraud classification. The project includes full steps such as data cleaning, visualization, model evaluation, and performance comparison using accuracy, precision, recall, F1-score, and confusion matrices.

📌**Nature of Data**

The dataset contains fictitious, artificially generated data.
It is designed only for educational, learning, and testing purposes.
It does not represent real individuals, banks, or financial entities.

📌**Purpose of Dataset Creation**

The dataset was created to provide a safe and realistic environment for practicing:
Data cleaning & preprocessing
Feature engineering
Exploratory Data Analysis (EDA)
Fraud detection model development
Model evaluation and comparison

📊**Dataset Information**

Total Rows: 3500

Total Columns: 12

Target Variable: Fraud_indicator

Includes features such as vehicle type, transaction amount, lane type, state code, day, hour, and more.

⚙️**Features of the Project**

✔ Data cleaning and preprocessing
✔ Handling categorical & numerical variables
✔ Exploratory Data Analysis (EDA) with visualizations
✔ Fraud vs Non-Fraud comparison
✔ Model training & testing
✔ Hyperparameter tuning with GridSearchCV
✔ Model evaluation using accuracy, precision, recall, F1-score
✔ Confusion matrix for classification performance
✔ Final model selection

🤖**Machine Learning Models Used**

Random Forest Classifier
Logistic Regression
K-Nearest Neighbors (KNN)
Decision Tree Classifier
Hyperparameter tuning is applied (especially for Random Forest) using GridSearchCV.

📈**Model Evaluation Metrics**

Each model is evaluated using:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

Example evaluation takeaway:

Random Forest performed best in terms of accuracy and balanced precision–recall for fraud classification.

📂 **Project Structure**
fraud-detection-ml/
│── data/
│── notebooks/
│── src/
│   ├── preprocessing.py
│   ├── model_training.py
│   ├── evaluation.py
│── models/
│── README.md
│── requirements.txt

🛠️ **Tech Stack**

Python

Pandas

NumPy

Scikit-Learn
Matplotlib
Seaborn
Jupyter Notebook


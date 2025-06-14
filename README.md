🧠 Thyroid Cancer Recurrence Prediction using Machine Learning
This project applies machine learning algorithms to predict thyroid cancer recurrence based on patient medical records. It includes data preprocessing, feature engineering (especially TNM stage encoding), visualization, model training (Logistic Regression, Naive Bayes, Decision Tree), hyperparameter tuning, and evaluation.

📂 Dataset
filtered_thyroid_data.csv

Contains patient data such as Age, Gender, TNM stage, Risk, and whether cancer recurred (Recurred column - target variable).

🚀 Project Structure
🔄 Data Preprocessing
Label Encoding for categorical features like Gender, Risk, and Response

TNM (Tumor, Node, Metastasis) stage feature extraction & scoring

Missing value imputation for engineered features

📊 Visualizations
Gender vs Recurrence count plot

Boxplot of Age distribution by recurrence

Bar plot of cancer stage vs recurrence count

Classification report visualized as a table

🤖 Models Implemented
Logistic Regression

Naive Bayes

Decision Tree with GridSearchCV for hyperparameter tuning

🧪 Evaluation Metrics
Accuracy Score

Classification Report (Precision, Recall, F1-Score)

Confusion Matrix

Decision Tree Visualization

📈 Requirements
Python 3.x

scikit-learn

pandas

matplotlib

seaborn

joblib

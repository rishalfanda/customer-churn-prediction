📊 Customer Churn Prediction

**Project Overview**
This project aims to predict customer churn using machine learning techniques. Churn prediction helps businesses identify customers who are likely to stop using a service, enabling proactive retention strategies.

📂 Dataset

  Training data: cell2celltrain.csv
  Testing data: cell2cellholdout.csv

The dataset contains customer behavior, usage patterns, and demographic information.

⚙️ Methodology

1. Data Cleaning
2. Handling Missing Values (using fillna())
3. Exploratory Data Analysis (EDA)
4. Feature Selection
5. Model Training:
  a. Random Forest
  b. Naive Bayes
6. Model Evaluation:
  a. Accuracy
  b. ROC Curve

📈 Results
1. Random Forest outperformed Naive Bayes
2. Better handling of complex relationships and high-dimensional data

📊 Key Insights
Customers with high dropped calls and customer care interactions are more likely to churn
Monthly contract users show higher churn probability
Usage behavior strongly influences churn

🧪 Models Used
1. Random Forest Classifier
2. Gaussian Naive Bayes

📉 **Evaluation Metrics**
1. Accuracy
2. ROC Curve

🚀 **How to Run**
git clone https://github.com/rishalfanda/customer-churn-prediction.git
cd customer-churn-prediction
pip install -r requirements.txt
jupyter notebook

**Future Improvements**: 
1. Hyperparameter tuning  
2. Feature engineering  
3. Deployment using Streamlit

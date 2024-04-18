# Real Estate Price Prediction Model

The world of real estate is intricate and always changing, making it tough for buyers, sellers, and agents to accurately determine the value of properties. The motivation behind this project is to address th complexity by developing an advanced Real Estate Price Prediction System. The goal is to create a powerful machine learning model that can deliver accurate property valuations based on data.

### 2.1 Data: 

The study utilizes a real estate dataset obtained from the Open-Source website, Kaggle, with a focus on Delhi, India. The dataset comprises 3,555 rows of data, which provides a substantial amount of information to analyze. The dataset consists of various property attributes, which were used for model training. 

To ensure accurate analysis, the collected data underwent preprocessing, including handling missing values, outliers, and feature scaling. In addition, categorical variables were transformed into binary representation using the One-hot encoding technique. Numerical variables were standardized using the StandardScaler method to ensure accurate analysis. By implementing these measures, the accuracy of the analysis is enhanced, and any potential distortions or inaccuracies that could arise are effectively mitigated. 

### 2.2 Modeling: 

The system employs a Random Forest Model with 500 decision trees as base estimators selected after rigorous testing and comparison with other algorithms like Linear Regression, XGBoost, and LASSO etc., Hyperparameter tuning is performed to optimize the model's performance and enhance prediction accuracy. 

### 2.3 Deployment: 

The trained model is deployed using Streamlit, a popular framework for building interactive web applications. The application is hosted on AWS, leveraging the cloud platform's scalability and reliability. 

### 🛠️ Tools Used:

[![My Skills](https://skillicons.dev/icons?i=aws,py&perline=3)](https://skillicons.dev)

# Data-Driven Estimation of Material Lifespan Using Machine Learning Models

🙍‍♂️ Author Saidul Islam | MS Research Fellow | Machine Learning & Chemometrics Enthusiast | M.Sc. in Inorganic Chemistry | Hajee Mohammad Danesh Science and Technology University, Dinajpur-5200

📌 Project Overview
This project presents a machine learning–based framework for predicting the lifespan of industrial materials using simulated manufacturing data. The objective is to provide a cost-effective, scalable alternative to traditional experimental durability testing by leveraging data-driven regression models.The study evaluates multiple ML algorithms and demonstrates that XGBoost delivers superior predictive performance for material lifespan estimation.


📂 Dataset
Source: Public Kaggle repository
Samples: 1,000 material components
Features: 15 variables including
Target: Material lifespan

⚙️ Preprocessing Steps
Missing value handling
One-hot encoding of categorical variables
Feature scaling using StandardScaler
Train–test split: 80:20 (random state = 42)

⚙️ Machine Learning Models
The following regression models were developed and compared:
Support Vector Regression (SVR)
Random Forest Regressor (RF)
Extreme Gradient Boosting (XGBoost)



📊 Model Performance
<img width="429" height="373" alt="image" src="https://github.com/user-attachments/assets/4ea2c124-3ced-4026-80de-97f5e48a6e75" />


✔ XGBoost achieved the highest accuracy and best generalization, with a 5-fold cross-validated R² of 0.964.

🔍 Model Interpretability
SHAP (SHapley Additive exPlanations) was applied to:
Identify key features influencing lifespan prediction
Improve transparency and trust in model decisions

🛠️ Tools & Libraries
Python
NumPy, Pandas
scikit-learn
XGBoost
SHAP
Matplotlib, Seaborn

🚀 Applications
Industrial material durability assessment
Manufacturing optimization
Materials informatics
Predictive maintenance plannin

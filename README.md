Titanic Survival Prediction

Overview
This project is based on the famous Titanic: Machine Learning from Disaster dataset from Kaggle.
The goal is to predict whether a passenger survived or not using machine learning models, based on features such as age, gender, ticket class, embarkation point, etc.

Project Workflow

Data Collection
Used Kaggle’s Titanic dataset.

Data Preprocessing & Cleaning
Handled missing values (Age, Cabin, Embarked).
Converted categorical variables (Sex, Embarked) using Label Encoding and One Hot Encoding.
Feature Engineering (Created new features like FamilySize, IsAlone).

Exploratory Data Analysis (EDA)
Visualized survival distribution by gender, class, age group.
Checked correlations using heatmaps.
Found meaningful patterns (e.g., Females had higher survival rates).

Model Building
Tried ML algorithm:
Logistic Regression


Model Evaluation
Used Accuracy Score, Confusion Matrix, and Cross-validation.
Achieved around 80% accuracy on test data.


Tech Stack
Programming Language: Python
Libraries Used:
Data Analysis → Pandas, NumPy
Visualization → Matplotlib, Seaborn
Machine Learning → Scikit-learn


Key Insights
Females had a significantly higher survival rate than males.
1st Class passengers had higher chances of survival compared to 2nd & 3rd class.
Passengers traveling alone were less likely to survive.
Age played an important role – children had better survival chances.


Future Improvements
Apply advanced models like XGBoost / LightGBM.
Hyperparameter tuning for better accuracy.
Deploy the model using Flask or Streamlit for a web-based prediction app.


Author: Avinash Paliwal
GitHub: https://github.com/ExpertAvinash
LinkedIn: https://www.linkedin.com/in/avinash-paliwal-a710a1253/

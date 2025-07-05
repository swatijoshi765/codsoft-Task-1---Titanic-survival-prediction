Titanic Survival Prediction:

This is a beginner-friendly machine learning project to predict the survival of passengers aboard the Titanic. Using data analysis and classification algorithms, we attempt to answer the question: "Would a passenger survive the Titanic disaster based on their features?"

Problem Statement:

The sinking of the Titanic is one of the most infamous shipwrecks in history. In this project, we use historical data to predict whether a given passenger survived the tragedy.

We analyze features like:

- Passenger Class
- Gender
- Age
- Fare
- Number of siblings/spouses aboard
- Number of parents/children aboard
- Port of Embarkation

Our goal is to build a machine learning model that accurately predicts survival.

Dataset:

The dataset used is the Titanic Dataset, commonly available on:
- https://www.kaggle.com/datasets/yasserh/titanic-dataset


It includes columns like:
- `PassengerId`, `Survived`, `Pclass`, `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, `Embarked`

Technologies Used:

- Python
- Pandas for data manipulation
- NumPy for numerical operations
- Matplotlib & Seaborn for data visualization
- Scikit-learn for machine learning algorithms

Machine Learning Model:

We used a Logistic Regression model as our baseline classifier.

Steps Involved:

1. Data Loading
2. Data Cleaning
   - Handling missing values
   - Dropping irrelevant features
   - Encoding categorical variables
3. Exploratory Data Analysis (EDA)
   - Survival rates by gender, class, etc.
   - Correlation heatmaps
4. Feature Selection
5. Model Building
   - Splitting data into train and test sets
   - Training Logistic Regression
6. Model Evaluation
   - Accuracy
   - Confusion Matrix
   - Classification Report

Accuracy:

The model was evaluated on a validation set and achieved an accuracy of approximately "0.8044692737430168".

How to Run:

1. Clone this repository:

git clone https://github.com/swatijoshi765/codsoft-Task-1---Titanic-survival-prediction.git

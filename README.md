# Elastic Net Regression for Insurance Cost Prediction

## Project Overview
This project focuses on predicting insurance costs using **Elastic Net Regression**, a supervised machine learning regression algorithm.
The project includes data preprocessing, model training, hyperparameter tuning using GridSearchCV, cross-validation, and model evaluation.

## Objectives
* Load and explore the insurance dataset
* Perform data preprocessing
* Prepare features for machine learning
* Split the data into training and testing sets
* Build an Elastic Net Regression model
* Tune model hyperparameters using GridSearchCV
* Evaluate model performance
* Perform cross-validation
* Predict insurance costs

## Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Machine Learning Details
**Type:** Supervised Machine Learning
**Problem:** Regression

**Algorithm:** Elastic Net Regression
Elastic Net combines the properties of **Lasso Regression (L1)** and **Ridge Regression (L2)** regularization.

## Key Learning Outcomes
Through this project, I practiced:
* Data preprocessing
* Feature encoding
* Supervised machine learning
* Regression
* Elastic Net Regression
* L1 and L2 regularization
* Hyperparameter tuning
* GridSearchCV
* Cross-validation
* Model evaluation
* Insurance cost prediction

---

# 1. Fuel Economy Analysis
Overview This project focuses on analyzing fuel economy data using machine learning techniques. The dataset contains various features related to vehicle specifications, fuel types, and fuel costs.

## Dataset :-
The dataset (vehicles.csv) used in this project consists of numerical and categorical fuel economy variables.

## Data Preprocessing :-
Imputation: Missing values in numerical columns are filled using the median value of each respective column. Outlier Removal: Outliers are identified and removed from the dataset based on the interquartile range (IQR) method. Scaling: Numerical features are scaled using both StandardScaler and MinMaxScaler techniques.

## Model Training :-
Three regression models are trained on the preprocessed dataset: Linear Regression Decision Tree Regressor Random Forest Regressor

## Evaluation :-
The trained models are evaluated using the R-squared (R2) metric on both training and testing datasets to assess their performance. R2 score measures the proportion of the variance in the dependent variable that is predictable from the independent variables.

## Results :-
Linear Regression: Achieved a training score of [0.99] and a testing score of [0.99]. Decision Tree Regressor: Achieved a training score of [1.0] and a testing score of [1.0]. Random Forest Regressor: Achieved a training score of [0.99] and a testing score of [0.99].

## Conclusion :-
All Models Performed well outperformed the other models with the highest testing score.


---

# Gradient Boosting Classification

## Project Overview
This project uses the **Mushroom dataset** to build a classification model using the **Gradient Boosting Classifier**.
The project covers data preprocessing, model training, hyperparameter tuning, feature importance analysis, and model evaluation using Python and Scikit-learn.

## Objectives
* Preprocess categorical mushroom data using one-hot encoding
* Split the dataset into training and testing sets
* Build a Gradient Boosting classification model
* Evaluate model performance using accuracy and cross-validation
* Identify the best hyperparameters using GridSearchCV
* Analyze important features
* Rebuild the model using selected important features
* Evaluate the final model using a confusion matrix and classification report

## Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Model
**Algorithm:** Gradient Boosting Classifier


## Key Learning Outcomes

Through this project, I practiced:
* Data preprocessing
* One-hot encoding
* Train-test splitting
* Gradient Boosting
* Cross-validation
* Hyperparameter tuning
* GridSearchCV
* Feature importance
* Confusion matrix
* Classification report
* Model evaluation

---

# 2. Titanic Survival Prediction
## Overview :-
This project aims to predict the survival of passengers aboard the Titanic using machine learning techniques. The dataset contains various features such as age, gender, ticket class, and cabin, which are used to train the models.

## Dataset :-
The dataset used in this project is provided as a CSV file named "Titanic.csv". It includes information about passengers aboard the Titanic, including whether they survived or not. The dataset contains both numerical and categorical features.

## Preprocessing :-
Loading the Dataset: Read the dataset using pandas. Handling Missing Values: For numerical columns, fill missing values with the median. For categorical columns, fill missing values with the mode. Outlier Removal: Identify outliers in numerical features. Remove outliers using the interquartile range (IQR) method. Feature Scaling: Scale numerical features using StandardScaler and MinMaxScaler. Feature Encoding: Encode categorical features using LabelEncoder. Model Training: Splitting the Data: Split the preprocessed data into training and testing sets (e.g., 70% training, 30% testing).

## Model Selection :-
Train three different classification models: Logistic Regression Decision Tree Classifier Random Forest Classifier.

## Results :-
The trained models achieve certain accuracy scores on both training and testing datasets, indicating their predictive

---

# 3. IPL Score Prediction using Deep Learning
## Overview :-
This project aims to predict the total score of an IPL match using Deep Learning techniques. The dataset contains various features such as batting team, bowling team, venue, batsman, bowler, runs, wickets, overs, striker, and non-striker, which are used to train the model.

## Dataset :-
The dataset used in this project is provided as a CSV file named "ipl_data.csv". It contains information about IPL matches, including batting and bowling details, runs, wickets, overs, players, venue, and total score.

## The following tools and technologies were used in this project:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras
- Jupyter Notebook

## Preprocessing :-
 1. Loading the Dataset: Read the dataset using pandas.
 2. Exploratory Data Analysis: Analyze the number of matches played at different venues and identify the top 10 batsmen and bowlers based on runs and wickets.
 3. Label Encoding: Convert categorical features such as batting team, bowling team, venue, batsman, and bowler into numerical values using LabelEncoder
 4. Feature Selection: Remove the date and match ID columns and analyze the correlation between the features using a correlation heatmap.
 5. Feature Scaling: Scale the selected features using MinMaxScaler.
 6. Splitting the Data: Split the preprocessed data into training and testing sets with 70% training data and 30% testing data.

## Model Selection :-
A Neural Network regression model is built using TensorFlow and Keras. The model consists of two hidden Dense layers with 512 and 216 neurons using ReLU activation, followed by an output layer with one neuron for predicting the total score. The model is compiled using the Adam optimizer and Huber Loss function. The model is trained for 10 epochs with a batch size of 50.

## Results :-
The trained model is used to predict the total IPL score on the test dataset. Model performance is evaluated using Mean Absolute Error (MAE). Training and validation loss are also plotted to observe the model's learning performance.


# Note :-
This projects was developed primarily to improve my practical experience and build strong hands-on expertise in Machine Learning tools and workflows.


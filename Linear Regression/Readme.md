
# Car Price Prediction using Machine Learning

## Project Overview
This project uses Machine Learning to predict the selling price of a used car based on features such as car name, company, manufacturing year, kilometers driven, and fuel type.

The goal is to build a regression model that estimates car prices from historical data and demonstrates a practical application of data preprocessing and predictive analytics.

## Objectives
- Clean and preprocess used-car data.
- Explore car features and prepare data for model training.
- Encode categorical variables for machine learning.
- Train a Linear Regression model to predict car prices.
- Evaluate model performance using the R² score.
- Save the trained model for future use.

## Technologies Used
- **Python**: Core programming language
- **Pandas & NumPy**: Data manipulation and preprocessing
- **Scikit-learn**: Data preprocessing, model training, and evaluation
- **Linear Regression**: Predictive machine learning algorithm
- **Pickle**: Saving the trained model
- **Jupyter Notebook**: Development and experimentation

## Dataset Features
The dataset contains information about used cars, including:

| Feature | Description |
|---|---|
| `name` | Car model name |
| `company` | Car manufacturer |
| `year` | Manufacturing year |
| `kms_driven` | Kilometers driven |
| `fuel_type` | Type of fuel |
| `Price` | Selling price (target variable) |

**Note:** The dataset file used in the notebook is `cars_data.csv`. Add this file to your repository if you have permission to share it.

## Project Workflow

1. **Data Loading:** Imported the dataset using Pandas.
2. **Data Cleaning:** Handled missing or invalid values, converted year and price columns to numeric formats, and cleaned kilometers-driven values.
3. **Feature Engineering:** Simplified car names to their first three words.
4. **Data Preparation:** Separated input features from the target variable and split the data into training and testing sets.
5. **Feature Encoding:** Used One-Hot Encoding to transform categorical features such as car name, company, and fuel type.
6. **Model Training:** Built a Scikit-learn pipeline combining preprocessing with Linear Regression.
7. **Model Evaluation:** Evaluated predictions using the R² score and experimented with different train-test splits.
8. **Model Saving:** Saved the trained pipeline as `LinearRegressionModel.pkl`.

## Model Evaluation
The model's performance is evaluated using the **R² score**, which measures how well the model explains variations in car prices.

The notebook also experiments with different random train-test splits to identify a split that produces a higher R² score. The resulting score should be validated on an appropriate holdout dataset before being treated as an estimate of real-world performance.


## Key Learnings
- Data cleaning and preprocessing with Pandas
- Feature engineering for machine learning
- One-Hot Encoding of categorical variables
- Building machine learning pipelines with Scikit-learn
- Training and evaluating regression models
- Saving trained models using Pickle

## 🔮 Future Improvements
- Compare Linear Regression with Random Forest and other regression algorithms.
- Evaluate performance using MAE, RMSE, and R².
- Use cross-validation and a separate test set for more reliable evaluation.
- Build an interactive web application for predicting used-car prices.
- Add input validation and realistic price prediction examples.


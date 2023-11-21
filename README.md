# Weather 🌦️ Prediction using Logistic Regression

This repository contains Python code for a simple weather prediction model using a Machine Learning that utilizes the logistic regression algorithm. The model is built to predict weather conditions based on historical data, specifically targeting Seattle weather.

Logistic Regression is a popular machine learning algorithm for binary classification tasks, to predict weather conditions (e.g., sun, rainy, fog) based on various features such as temperature, humidity, wind speed, and atmospheric pressure. The aim is to develop a model that accurately predicts the weather based on historical data.

## Dataset

The dataset used in this project contains historical weather data collected over several years. It includes features such as temperature, humidity, wind speed, atmospheric pressure, and the corresponding weather condition labels. The dataset is stored in a CSV format and is included in the data directory of this repository.

## Requirements

To run the code, you need to have the following libraries installed:

- Python
- Numpy
- Pandas
- scikit-learn

You can install the required libraries using pip:

```bash
   pip install scikit-learn pandas numpy
```

## Perform the tasks

It performs the following tasks:

**1. Data Preparation:** Loads the dataset from the file seattle-weather.csv and preprocesses it by encoding the categorical weather labels using LabelEncoder.

**2. Feature Selection:** Selects relevant features (temperature_max, temperature_min, wind_speed) for weather prediction.

**3. Data Splitting:** Splits the dataset into training and testing sets using train_test_split from scikit-learn.

**4. Data Normalization:** Utilizes StandardScaler to standardize the feature values for better model performance.

**5. Logistic Regression Model Training:** Constructs a logistic regression model using LogisticRegression from scikit-learn and fits it to the training data.

**6. Model Evaluation:** Predicts weather conditions on the test dataset and evaluates model performance using accuracy metrics.

**7. User Input Prediction:** Asks the user to input new weather parameters (**maximum temperature**, **minimum temperature**, and **wind speed**) and predicts the corresponding weather condition using the trained logistic regression model.

## Output

**Ask maximum temperature**

![image](https://github.com/Vicky9890/Weather_Prediction_Analysis/assets/138276603/82ba05f5-cfc7-4179-8c3e-6244c3935d15)

**Ask minimum temperature**

![image](https://github.com/Vicky9890/Weather_Prediction_Analysis/assets/138276603/42956b0a-4056-4c5c-84eb-fd12297fc1c4)

**Ask wind speed**

![image](https://github.com/Vicky9890/Weather_Prediction_Analysis/assets/138276603/4888ecc5-7536-4e4a-96b3-4203cb64ceb5)

**Result**

![image](https://github.com/Vicky9890/Weather_Prediction_Analysis/assets/138276603/d2670646-ad30-4c12-ab08-498f262bf87b)

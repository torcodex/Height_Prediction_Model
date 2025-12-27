# Height_Prediction_Model

This project uses Linear Regression to predict a person’s height (cm) based on their weight (kg) using a CSV dataset.

🔹 Steps Explained Simply
1️⃣ Import Required Libraries

pandas, numpy → handle data

matplotlib → create graphs

sklearn → build the machine learning model

2️⃣ Load the Dataset

Reads the weight-height.csv file into a DataFrame

Checks for missing values and duplicate rows

3️⃣ Data Cleaning

Creates a copy of the data

Removes the Gender column (not needed for prediction)

4️⃣ Unit Conversion

Converts:

Height from inches → centimeters

Weight from pounds → kilograms

Removes old height and weight columns

5️⃣ Data Visualization

Histograms show how height and weight values are distributed

Scatter plot shows the relationship between height and weight

6️⃣ Correlation Check

Finds how strongly height and weight are related

7️⃣ Prepare Data for Model

Weight_kg → input (X)

Height_cm → output (Y)

8️⃣ Train Linear Regression Model

The model learns a straight-line relationship

Finds:

Slope (m) → how height changes with weight

Intercept (c) → starting point of the line

9️⃣ Prediction & Error Analysis

Predicts heights using the model

Calculates prediction error

Plots:

Weight vs Error

Actual vs Predicted values

🔟 Save & Load the Model

Saves the trained model using pickle

Reloads the model and makes predictions on new data

✅ Outcome

The program successfully learns the relationship between weight and height and can predict heights for new weight values.



# Intern Details

Name: Riya Chauhan

Intern ID:CTIS2027

Domain: Data Analytics

Duration-12 weeks

Mentor: Neela Santhosh Kumar

# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING

# Project Overview

This project performs predictive analysis on the Boston Housing dataset using Python and Machine Learning. The main goal is to build a model that can predict house prices based on selected features from the dataset.

The project uses a linear regression model to learn patterns in the dataset and make predictions. By training the model on historical data, it can estimate house prices for new inputs. This demonstrates the practical use of Machine Learning in predicting outcomes and understanding relationships between variables.

The dataset includes features such as rm (average number of rooms per house) and lstat (% of lower status population) as input, and medv (median house value) as the target. Using these features, the model predicts house prices accurately and compares them to actual values.

The project also includes a visual comparison of actual vs predicted house prices using a bar graph. This visualization makes it easy to see how well the model performs and where predictions differ from actual prices.

The task was completed using Google Colab, which provides a convenient environment to run Python code and visualize outputs.

# Dataset

File: housing.csv

Features used: rm (rooms), lstat (lower status %)

Target column: medv (median house price)


# Analysis Performed

Imported required libraries: pandas, numpy, matplotlib, sklearn

Loaded the dataset successfully

Selected input features (rm, lstat) and target (medv)

Split dataset into training and testing sets (80%-20%)

Trained a Linear Regression model on the training data

Predicted house prices for testing data

Calculated Mean Absolute Error (MAE) to measure prediction accuracy

Created a bar graph comparing actual vs predicted prices for first 10 samples

This process demonstrates the complete workflow of building a predictive model, from data loading to evaluation and visualization.

# Key Insights

The model was trained successfully and produced predictions that closely match actual house prices

Sample predictions for first 10 records show the model’s ability to estimate prices accurately

Mean Absolute Error calculated: *** (Add your MAE here, e.g., 4.3)

Visualization shows that most predicted values are very close to actual prices, validating model performance

This task highlights how Machine Learning models can extract insights and predict outcomes, even with simple features, and how visualizations help interpret results.

# Tools & Technologies Used

Python

Google Colab

Pandas

NumPy

Matplotlib

Scikit-learn

# Project Files

predictive_analysis.ipynb → Colab notebook with full code

housing.csv → dataset used

model_output.png → graph showing Actual vs Predicted Prices

README.md → project description

# How to Run

Open predictive_analysis.ipynb in Google Colab or Jupyter Notebook

Install required libraries:

pip install pandas numpy matplotlib scikit-learn

Run all cells sequentially

Outputs include predicted prices, Mean Absolute Error, and a graph comparing actual vs predicted values

# output
<img width="746" height="674" alt="Image" src="https://github.com/user-attachments/assets/48f8b0c9-23bd-4595-a66f-3ec38051a668" />
<img width="841" height="470" alt="Image" src="https://github.com/user-attachments/assets/dd2f3f52-2f35-4e0f-bbd3-41e8dbd2e256" />

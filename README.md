# Predicting Expected CTC for Job Applicants Using Linear Regression

This project builds a machine learning model to **predict the expected CTC (Cost to Company) for job applicants** using linear regression. The dataset, provided by Launched Global, is included in this repository.

## Features

- Data loading and preprocessing
- Exploratory data analysis (EDA) with visualizations
- Outlier detection and removal
- Model training and evaluation (R² score, RMSE)
- Model saving for future use
- Visualization of predictions and residuals

## Dataset

- **File:** `expected_ctc.csv`
- **Source:** Provided by Launched Global for this project
- **Included:** Yes

## Usage

### 1. Install Requirements

Make sure you have Python 3.x and the following packages installed:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

**You can install them using:**
'''pip install pandas numpy scikit-learn matplotlib seaborn'''

### 2. Run the Code

- Open the script or Jupyter Notebook and run all cells/lines in order.

### 3. Outputs

- R² score and RMSE for model evaluation
- Saved model file
- Plots for EDA and model diagnostics

## Code Overview

Below are short explanations for the main code sections:

- **Import Libraries:**  
  Loads all necessary libraries for data manipulation, visualization, and machine learning.

- **Load Dataset:**  
  Reads the `expected_ctc.csv` file into a pandas DataFrame.

- **Initial Data Inspection:**  
  Displays the first few rows and basic information about the dataset.

- **EDA and Visualization:**  
  Uses histograms, boxplots, and scatter plots to explore feature distributions and relationships.

- **Outlier Detection and Removal:**  
  Identifies and removes outliers using statistical methods to improve model robustness.

- **Feature Selection & Engineering:**  
  Selects relevant columns and applies any necessary transformations.

- **Data Splitting:**  
  Splits the data into training and testing sets to evaluate model generalization.

- **Model Training:**  
  Fits a linear regression model to the training data.

- **Model Evaluation:**  
  Calculates R² score and RMSE on the test set to assess model performance.

- **Model Saving:**  
  Serializes and saves the trained model for future predictions.

- **Prediction and Visualization:**  
  Generates predictions on the test set and visualizes results with scatter plots and residual plots.

## Results

- **R² score:** Indicates how well the model explains the variance in expected CTC.
- **RMSE:** Measures the average prediction error in the same units as CTC.
- **Plots:** Visualizations of feature relationships, predictions, and residuals.

## Notes

- The dataset is included and ready for use.
- Model and results are reproducible with the provided code and requirements.


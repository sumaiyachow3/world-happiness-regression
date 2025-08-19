# world-happiness-regression
Supervised regression on the World Happiness Report 2018 dataset to predict happiness scores.

## Define and Solve a Machine Learning Problem – World Happiness Report 2018

This project demonstrates an end-to-end supervised regression workflow using the World Happiness Report 2018 (WHR2018Chapter2OnlineData.csv) dataset. The notebook explores, preprocesses, and models the data to predict happiness-related outcomes.

### Overview

The notebook includes the following:

- Problem Definition
- Predicting target variables related to happiness scores using regression.
- Input: socioeconomic and well-being factors (e.g., GDP, life expectancy, social support).
-  Output: a continuous value representing the target (happiness-related metric).
-  Data Preparation
-  Data loading with Pandas
-  Exploratory Data Analysis (EDA) using Matplotlib and Seaborn
-  Handling missing values and scaling features with StandardScaler
-  Model Development
-  Building a regression model with Scikit-learn
-  Splitting data into training and testing sets
-  Evaluation
-  Reporting Loss and Mean Absolute Error (MAE) as performance metrics

### Requirements

Install dependencies with:
  pip install pandas numpy matplotlib seaborn scikit-learn jupyter

### Usage

1. Clone this repository or download the notebook.

2. Place the dataset WHR2018Chapter2OnlineData.csv in the project directory.

3. Launch Jupyter and open the notebook:
      jupyter notebook "DefineAndSolveMLProblem (4).ipynb"

4. Run the notebook cells step by step to reproduce results.

### Dataset

Name: World Happiness Report 2018 

Description: Contains country-level data on factors influencing happiness, including GDP per capita, life expectancy, social support, corruption, generosity, and freedom.

### Results

The regression model outputs:
- Loss (measure of prediction error)
- Mean Absolute Error (MAE) (average difference between predicted and actual values)
- R2 Score

These metrics provide insight into model performance and predictive accuracy.

### Future Improvements

- Experiment with different regression models (e.g., Random Forest, Gradient Boosting, Neural Networks)
- Add cross-validation to improve evaluation reliability

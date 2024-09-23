# Income Classification Using Logistic Regression

## Overview
This project involves building a logistic regression model to classify individuals based on their income level using demographic and financial data. The primary objective is to predict whether an individual's income exceeds a certain threshold based on various features such as age, education, occupation, and more. This project demonstrates my skills in data preprocessing, exploratory data analysis, and binary classification using logistic regression.

## Project Structure


## Problem Statement
Income classification is an important task for many applications, such as targeted marketing and social studies. By using logistic regression, this project aims to build a predictive model that can accurately classify individuals into income categories based on a set of features.

## Dataset
- **Source:** [Link to dataset source, e.g., UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Adult)
- **Description:** The dataset contains demographic information such as age, gender, education, occupation, and hours worked per week, along with a binary label indicating whether an individual's income is above or below a specified threshold.

## Key Features
- **Age:** Age of the individual.
- **Education:** Highest level of education attained.
- **Occupation:** Current occupation.
- **Hours-per-week:** Number of hours worked per week.
- **Capital-gain and Capital-loss:** Financial gains or losses.

## Methodology
1. **Data Cleaning:** Handling missing values, outlier detection, and encoding categorical variables.
2. **Exploratory Data Analysis (EDA):** Analyzing the distribution of features and their relationship with the target variable.
3. **Feature Engineering:** Creating new features and selecting the most relevant ones for model building.
4. **Model Building:** Implementing logistic regression for binary classification.
5. **Model Evaluation:** Using metrics like accuracy, precision, recall, and F1-score to evaluate model performance.

## Technologies Used
- **Python:** For data processing and analysis.
- **Pandas & NumPy:** For data manipulation and numerical operations.
- **Matplotlib & Seaborn:** For data visualization.
- **Scikit-learn:** For implementing and evaluating logistic regression models.

## Results
The logistic regression model achieved an accuracy of `X.XX` on the test set, with a precision of `X.XX` and recall of `X.XX`. The model's performance was evaluated using a confusion matrix and ROC-AUC curve to assess its ability to distinguish between the two income classes.

## How to Run
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Income-Classification-Logistic-Regression.git
2. **Navigate to the project directory:**
   ```bash
   cd Income-Classification-Logistic-Regression
3. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
4. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook notebooks/Income-Classification-Using-Logistic-Regression.ipynb

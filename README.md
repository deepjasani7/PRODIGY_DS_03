# Customer Purchase Prediction Using Decision Tree Classifier

## Repository Overview
This repository contains a project aimed at predicting whether a customer will purchase a product or service based on their demographic and behavioral data. Using a decision tree classifier, this analysis utilizes the Bank Marketing dataset from the UCI Machine Learning Repository.

## Files in the Repository
- **bank-additional.csv**: The dataset used for prediction. This dataset contains demographic and behavioral data of customers, including information about previous marketing campaigns and the outcome of those campaigns.
- **Task_3.ipynb**: A Jupyter Notebook containing the code to build and evaluate a decision tree classifier for predicting customer purchase behavior.

## Dataset Overview
The dataset (`bank-additional.csv`) contains the following columns:
- `age`: Age of the customer (numeric).
- `job`: Type of job (categorical, e.g., admin, technician, etc.).
- `marital`: Marital status (categorical, e.g., single, married, divorced).
- `education`: Level of education (categorical, e.g., primary, secondary, tertiary).
- `default`: Whether the customer has credit in default (binary: yes/no).
- `housing`: Whether the customer has a housing loan (binary: yes/no).
- `loan`: Whether the customer has a personal loan (binary: yes/no).
- `contact`: Type of communication used for contact (categorical, e.g., cellular, telephone).
- `month`: Last contact month of the year (categorical).
- `day_of_week`: Last contact day of the week (categorical).
- `duration`: Duration of the last contact in seconds (numeric).
- `campaign`: Number of contacts performed during this campaign for this client (numeric).
- `pdays`: Number of days since the client was last contacted (999 means the client was not previously contacted) (numeric).
- `previous`: Number of contacts before this campaign (numeric).
- `poutcome`: Outcome of the previous marketing campaign (categorical: success, failure, nonexistent).
- `emp.var.rate`: Employment variation rate (numeric).
- `cons.price.idx`: Consumer price index (numeric).
- `cons.conf.idx`: Consumer confidence index (numeric).
- `euribor3m`: Euribor 3-month rate (numeric).
- `nr.employed`: Number of employees (numeric).
- `deposit`: Target variable indicating whether the client subscribed to a term deposit (binary: yes/no).

### Key Information:
- The dataset contains a mix of categorical and numerical features.
- The target variable is binary, indicating whether a customer purchased the product (term deposit).

## Project Overview
The main objective of this project is to build a decision tree classifier to predict customer purchase behavior based on various demographic and behavioral attributes. Key steps include:
1. **Data Loading**: Load the dataset using Python's `pandas` library.
2. **Data Cleaning**: Handle any missing values and perform necessary data preprocessing (e.g., encoding categorical variables).
3. **Exploratory Data Analysis (EDA)**: Analyze the data to identify patterns and trends, including visualizations of important features.
4. **Model Building**: Create a decision tree classifier using `scikit-learn`.
5. **Model Evaluation**: Evaluate the performance of the model using appropriate metrics (accuracy, precision, recall, etc.).

### Steps in the Notebook:
1. **Load Libraries**: Import required libraries such as `pandas`, `numpy`, `matplotlib`, `seaborn`, and `scikit-learn`.
2. **Load Dataset**: Read the `bank-additional.csv` file into a DataFrame.
3. **Data Cleaning**: Check for missing values and data types, and apply transformations as necessary.
4. **EDA**: Visualize relationships between variables and the target variable.
5. **Train-Test Split**: Split the data into training and testing sets.
6. **Build Decision Tree**: Train a decision tree classifier on the training set.
7. **Evaluate Model**: Use the test set to evaluate model performance and visualize the decision tree.

## How to Run the Notebook
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/deepjasani7/PRODIGY_DS_03/tree/main

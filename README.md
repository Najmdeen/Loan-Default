# Loan Default Prediction

## Project Overview
This project aims to build and evaluate machine learning models to predict loan defaults. The dataset used includes various features like borrower's income, gender, loan purpose, credit score, etc. The project involved data cleaning, exploratory data analysis (EDA), feature engineering, model development, and hyperparameter tuning.

## Data
The dataset used in this project contains information about loan borrowers and their repayment history. Key features include income, gender, loan purpose, credit score, and more. The target variable is loan default status.

## Methodology
1. **Data Cleaning**: Handled missing values and addressed multicollinearity.
2. **Exploratory Data Analysis**: Analyzed distributions, relationships, and correlations in the data.
3. **Feature Engineering**: Encoded categorical variables and scaled numerical features.
4. **Model Development**: Trained various models including Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, and SVM.
5. **Hyperparameter Tuning**: Used Grid Search with cross-validation for Random Forest and Gradient Boosting models.
6. **Model Evaluation**: Assessed model performance using accuracy, precision, recall, F1 score, and ROC AUC.

## Results
Both Random Forest and Gradient Boosting models demonstrated excellent predictive performance with near-perfect scores across all evaluation metrics.

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## How to Run
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Jupyter notebooks to train and evaluate models.

## Repository Structure
- `data/`: Contains the dataset used in the project.
- `notebooks/`: Jupyter notebooks for model development and evaluation.
- `requirements.txt`: List of libraries required to run the project.
- `README.md`: Overview and instructions for the project.

## License
This project is licensed under the terms of the MIT license.

# Employee-Attrition-Prediction
This project aims to develop a predictive model to identify the likelihood of employee attrition within a company using HR data. By leveraging advanced classification techniques and feature engineering specific to HR analytics, the model predicts whether an employee is likely to leave the organization. 

## Overview
Employee Attrition Prediction is a project aimed at developing a predictive model to identify the likelihood of employee attrition within a company using HR data. The project utilizes advanced classification techniques and feature engineering specific to HR analytics to predict whether an employee is likely to leave the organization.

## Dataset
The dataset used for this project is the IBM HR Analytics Employee Attrition dataset, which includes various attributes such as employee demographics, job satisfaction metrics, and performance indicators. You can find the dataset [here](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset).

## Requirements
- Python 3.x
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/employee-attrition-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd employee-attrition-prediction
   ```
3. Download the dataset from the provided link and place it in the project directory.
4. Run the `employee_attrition_prediction.py` script to train and evaluate the predictive model:
   ```bash
   python employee_attrition_prediction.py
   ```

## Results
- The script `employee_attrition_prediction.py` performs the following tasks:
  - Data preprocessing: Handling missing values, encoding categorical variables, and splitting the data into training and testing sets.
  - Baseline model training and evaluation.
  - Hyperparameter tuning using RandomizedSearchCV to optimize the model.
  - Training an optimized model and evaluating its performance.
  - Training a balanced model to handle class imbalance and evaluating its performance.
  - Visualizing feature importances.
  - Saving the optimized model for future use.
- The results of model evaluation, including accuracy, confusion matrix, and classification report, are displayed in the console output.

## Contributors
- [Khushi Sapkal](https://github.com/Khushi136)

## License
This project is licensed under the [MIT License](LICENSE).

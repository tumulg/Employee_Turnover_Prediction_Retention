# Predicting Employee Turnover and Enhancing Retention Strategies at Salifort Motors

This project focuses on analyzing employee survey data to predict employee turnover at Salifort Motors. The goal is to identify key factors influencing turnover and provide actionable insights to improve employee retention, enhance job satisfaction, and reduce hiring and training costs.

## Project Overview

Employee turnover is a critical challenge for many organizations. By analyzing employee satisfaction, performance, work environment, and other factors, this project aims to predict which employees are most likely to leave the company and suggest strategies for improving retention.

### Key Goals:
1. **Predict Employee Turnover**: Build a model that predicts the likelihood of an employee leaving based on various factors.
2. **Identify Influencing Factors**: Understand which variables have the greatest impact on turnover.
3. **Enhance Retention Strategies**: Provide actionable recommendations for improving employee retention.

### Workflow:
1. **Data Preparation**:
   - Import necessary libraries.
   - Load and inspect the dataset for initial analysis.

2. **Data Exploration and Cleaning**:
   - Handle missing values, if any, and ensure data consistency.
   - Remove any outliers to improve data quality.

3. **Exploratory Data Analysis (EDA)**:
   - Visualize trends and correlations between features and employee turnover.
   - Investigate which factors are most strongly associated with employees leaving.

4. **Model Building and Evaluation**:
   - Split the dataset into training and testing subsets.
   - Train a Logistic Regression model to predict turnover.
   - Evaluate the model using accuracy, precision, recall, F1-score, confusion matrix, and classification report.

5. **Conclusion**:
   - Summarize key insights and suggest strategies for improving employee retention based on the analysis.

## Dataset Description

The dataset contains 14,999 rows, each representing an employee. It includes 10 columns with information about the employee's satisfaction, performance, and work experience.

| Column Name            | Type    | Description                                                       |
|------------------------|---------|-------------------------------------------------------------------|
| `satisfaction_level`   | float64 | Employee's self-reported satisfaction level [0-1].               |
| `last_evaluation`      | float64 | Score of the employee's last performance review [0-1].           |
| `number_project`       | int64   | Number of projects the employee contributes to.                  |
| `average_monthly_hours`| int64   | Average number of hours worked per month.                        |
| `time_spend_company`   | int64   | Number of years the employee has been with the company.          |
| `work_accident`        | int64   | Whether the employee experienced an accident at work (0 or 1).   |
| `left`                 | int64   | Whether the employee left the company (0 = No, 1 = Yes).         |
| `promotion_last_5years`| int64   | Whether the employee was promoted in the last 5 years (0 or 1).  |
| `department`           | str     | Employee's department (e.g., sales, technical, etc.).            |
| `salary`               | str     | Employee's salary category (low, medium, high).                  |

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - Data Manipulation: Pandas, NumPy
  - Data Visualization: Matplotlib, Seaborn
  - Machine Learning: Scikit-learn (for Logistic Regression, Model Evaluation, and Classification Metrics)
- **Development Environment**: Jupyter Notebooks

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- **Kaggle** for providing the employee survey dataset.
- The Python and data science community for the tools and resources used in this project.

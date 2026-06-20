# Salary Prediction Using Ensemble Learning
Machine Learning project for salary prediction using multiple regression models and ensemble learning techniques.
## Project Overview
This project aims to predict employee salaries using machine learning regression techniques. Multiple models and compared to identify the best-performing approach for salary prediction.

## Dataset Description
The dataset contains approximately 250,000 records and includes features such as job title, company size, location, remote work status, experience years, skills count, certifications, and salary.

## Exploratory Data Analysis
Exploratory Data Analysis (EDA) was performed to understand the dataset. A histogram was used to analyze salary distribution and a boxplot was used to identify potential outliers. The dataset contained no missing values.

## Data Preprocessing
The salary column was selected as the target variable. Categorical variables were converted into numerical format using One-Hot Encoding with pandas get_dummies(). The dataset was then split into training and testing sets using an 80:20 ratio.

## Machine Learning models Used

### Linear Regression
Linear Regression was used as the baseline model for salary prediction.

### Decision Tree Regressor
Decision Tree Regressor was trained to capture non-linear relationships within the dataset.

### Random Forest Regressor
Random Forest Regressor was used as an ensemble learning method combining multiple decision trees.

### Gradient Boosting Regressor
Gradient Boosting Regressor was trained to improve prediction accuracy through sequential learning.

## Model Performance Comparison
| Model                      | MAE     | R² Score |
|----------------------------|---------:|---------|
| Linear Regression           | 5436.10 | 0.9635  |
| Decision Tree Regressor     | 7983.79 | 0.9213  |
| Random Forest Regressor     | 5693.02 | 0.9609  |
|Gradient Boosting Regressor  | 8871.42 | 0.8994  |

## Best Model Selection
Based on model evaluation metrics, Linear Regression achieved the highest R² score (0.9635) and the lowest MAE (5436.10). Therefore, it was selected as the best-performing model for this dataset.

## Conclusion
The project successfully predicted salaries using multiple machine learning models. Model comparison showed that Linear Regression performed better than the ensemble models for this dataset.

## Future Scope
Future improvements may include hyperparameter tuning, feature engineering, advanced ensemble methods, and deployment of the trained model as a web application.

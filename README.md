# Loan_prediction_ML
"Loan Status Prediction using ML" project, tailored to highlight the key aspects of the project as shown in the provided code and documents. The description is designed to be clear, informative, and appealing to potential viewers, such as recruiters or collaborators, while summarizing the project's purpose, methodology, and outcomes






#                                                                  Loan Status Prediction using Machine Learning



## Project Overview

This project develops a machine learning model to predict whether a loan applicant is eligible for a loan based on features such as income, credit history, education, and marital status. Using a Kaggle dataset with over 600 records, a Support Vector Machine (SVM) classifier is implemented to automate loan approval decisions, achieving a test accuracy of 83.3%. The project demonstrates proficiency in data preprocessing, feature engineering, exploratory data analysis (EDA), and model evaluation, with potential applications in streamlining financial workflows.

## Key Features

- **Data Preprocessing**: Handled missing values by dropping rows with null entries and converted categorical features (e.g., Gender, Married, Education) to numerical values using label encoding. Replaced '3+' in the Dependents column with 4 for consistency.
- **Exploratory Data Analysis (EDA)**: Utilized Seaborn's `countplot` to visualize relationships, revealing higher loan approval rates for graduates and married individuals.
- **Model Training**: Employed an SVM classifier with a linear kernel using Scikit-learn, trained on an 80-20 train-test split.
- **Performance**: Achieved 79.8% training accuracy and 83.3% test accuracy, indicating robust model generalization without overfitting.
- **Business Impact**: Enables automated loan approval decisions, reducing manual processing for financial institutions.

## Dataset

- **Source**: Kaggle dataset (`loan_prediction_ML.csv`) with 614 rows and 13 columns, including features like `Gender`, `Married`, `Dependents`, `Education`, `ApplicantIncome`, `LoanAmount`, `Credit_History`, and `Loan_Status`.
- **Preprocessing Steps**:
  - Dropped `Loan_ID` column as it was irrelevant.
  - Handled missing values using `dropna()`.
  - Encoded categorical variables (e.g., `Loan_Status`: 'Y'→1, 'N'→0; `Gender`: 'Male'→1, 'Female'→0).
  - Replaced '3+' in `Dependents` with 4.

## Tools and Libraries

- **Programming Language**: Python 3.8+
- **Libraries**:
  - `pandas`: Data manipulation and preprocessing
  - `numpy`: Numerical operations
  - `seaborn` and `matplotlib`: Data visualization
  - `scikit-learn`: SVM model implementation and evaluation



## Results

- **Training Accuracy**: 79.8%
- **Test Accuracy**: 83.3%
- **Insights**:
  - Graduates have a higher likelihood of loan approval compared to non-graduates.
  - Married individuals show a higher approval rate, possibly due to dual income contributions.
- **Application**: The model can be integrated into a financial institution's workflow to automate loan approval processes, improving efficiency and reducing manual effort.

## Visualizations

Below are sample visualizations from the EDA:
- **Education vs. Loan Status**: Shows higher approval rates for graduates.
  ![Education vs Loan Status](images/education_loan_status.png)
- **Marital Status vs. Loan Status**: Indicates married applicants have a higher approval rate.
  ![Marital Status vs Loan Status](images/married_loan_status.png)


## Future Improvements

- Experiment with other machine learning models (e.g., Random Forest, XGBoost) to improve accuracy.
- Implement hyperparameter tuning for the SVM model using GridSearchCV.
- Develop a web application to allow real-time loan eligibility predictions.
- Incorporate additional features or datasets to enhance model robustness.



## Contact

For questions or contributions, feel free to reach out:
- **Email**: [anaytondar55@gmail.com](mailto:anaytondar55@gmail.com)
- **LinkedIn**: [linkedin.com/in/anay-tondar-66b06525b](https://www.linkedin.com/in/anay-tondar-66b06525b)
- **GitHub**: [github.com/Anay100](https://github.com/Anay100)

-----

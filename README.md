# Credit Risk Analysis

This project involves analyzing credit data to predict the likelihood of individuals securing a loan. The analysis leverages machine learning techniques to identify the most influential factors in loan approval and compares the performance of different classification models.

## Project Overview

- **Data Source**: A dataset of 1,000 users' credit-related information.
- **Goal**: To predict which users are more likely to get approved for a loan based on various financial and personal factors.
- **Techniques Used**:
  - Data Analysis: Conducted an in-depth analysis using Python to explore user data.
  - Feature Importance: Utilized LIME and SHAP to identify the most influential factors in the bank's loan approval decisions.
  - Model Comparison: Compared the performance of XGBoost with KNN and evaluated them using AUC (Area Under the Curve).

## Tools and Technologies

- **Programming Languages**: Python
- **Libraries**:
  - XGBoost
  - KNN
  - LIME
  - SHAP
  - Scikit-learn
  - Pandas
  - Matplotlib

## Project Highlights

- **Performance Improvement**: Achieved a 10% improvement in model performance with XGBoost compared to KNN, as measured by AUC.
- **Feature Analysis**: Leveraged LIME and SHAP to gain insights into the factors most influencing the bank's decisions, identifying areas where users could improve to increase their chances of loan approval.


### Running the Project

1. Load the dataset (provided in the `data/` directory or specify your own).
2. Run the Jupyter Notebook or the Python script to preprocess the data, train the model, and evaluate the results.

### Results

The final model using XGBoost outperformed KNN, achieving a 10% higher AUC score. Detailed performance metrics and visualizations can be found in the notebook/script.


## Contact

For any inquiries or suggestions, please contact:
- **Hongyang Zhang**
- Email: [hzha464@aucklanduni.ac.nz](mailto:hzha464@aucklanduni.ac.nz)

## End to End machine learning project

This project focuses on predicting student performance based on features such as Gender, Race/Ethnicity, Parental Level of Education, Lunch Type, Test Preparation Status, and scores in Math, Reading, and Writing. The objective was to identify patterns influencing performance and build a machine learning model for accurate predictions. Multiple models were evaluated to find the most effective one.

# Data Transformation and Preprocessing:

Handling Missing Values:

Missing data was imputed using appropriate techniques, such as filling with mean, median, or mode based on feature type.

Feature Encoding:

Categorical features like Gender, Race/Ethnicity, Parental Level of Education, Lunch, and Test Preparation Status were converted into numerical values using One-Hot Encoding or Label Encoding to make them suitable for machine learning algorithms.

Feature Scaling:

Numerical features like Math, Reading, and Writing Scores were standardized using StandardScaler for consistent feature scaling.

Derived Features:

Average performance across the three scores was calculated as an additional feature to capture overall student performance.

# Model Evaluation

Machine learning models such as Linear Regression, Random Forest, Support Vector Machines (SVM), and Gradient Boosting were trained and tested.

Performance metrics like Mean Absolute Error (MAE), R² Score, and Accuracy (for classification tasks) were used for evaluation.

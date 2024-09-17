# predictive-analytics-for-loan-defaults

Analyses LendingClub loan data to identify and understand patterns in defaulted loans by examining specific loan statuses such as charged-off or late payments and utilising ML techniques for predictive analysis.

# Project Objective's

- Aims to analyze a large loan dataset using PySpark, focusing on efficient data processing and transformations. It leverages PySpark functions like groupBy, count, isnan, and col to handle missing data, perform data cleaning, and prepare the dataset for machine learning models.
- Data preprocessing steps such as identifying features with more than 50% missing values and removing or imputing those features. It also uses PySpark's StringIndexer and VectorAssembler for feature encoding and vectorisation, critical for preparing the data for machine learning models.
- Implements machine learning models, including Logistic Regression, to predict loan defaults. It involves setting up the model pipeline using PySpark’s CrossValidator and ParamGridBuilder to fine-tune the hyperparameters and evaluate model performance using metrics like ROC-AUC.
- Visualize data using libraries like Matplotlib and Seaborn to generate insights about the loan data, such as distributions of loan statuses and relationships between features, enhancing understanding and communication of the data insights.

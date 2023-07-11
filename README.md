# Supervised Learning Project

## Project/Goals

The primary objective of the project is to extract valuable insights from the datasets and effectively communicate them to stakeholders. This involves employing suitable visualizations and metrics to address specific business questions, enabling stakeholders to make informed decisions based on the obtained insights.

## Process

#### Step 1: EDA - Exploratory Data Analysis:
Conduct an exploratory data analysis on the diabetes dataset. Choose the visualizations I want to use, and my analysis cover the following tasks mostly:

- Are there any missing values in the dataset?
- How are the predictor variables related to the outcome variable?
- What is the correlation between the predictor variables?
- What is the distribution of each predictor variable?
- Are there any outliers in the predictor variables?
- How are the predictor variables related to each other?
- Is there any interaction effect between the predictor variables?
- What is the average age of the individuals in the dataset?
- What is the average glucose level for individuals with diabetes and without diabetes?
- What is the average BMI for individuals with diabetes and without diabetes?
- How does the distribution of the predictor variables differ for individuals with diabetes and without diabetes?
- Are there any differences in the predictor variables between males and females (if gender information is available)?

#### Step 2: Preprocessing & Feature Engineering
Perform preprocessing on the given dataset
- Handling missing values
- Handling outliers
- Scaling and normalization
- Feature Engineering
- Handling imbalanced data

#### Step 3: Training ML Model
Build a machine learning model to predict the outcome variable. I selected Logistic Regression model and Random Forest Classifier model.

- Train the models: Train the selected models on the training set.
- Model evaluation: Evaluate the trained models on the testing set using appropriate evaluation metrics, such as accuracy, precision, recall, F1-score, and ROC-AUC.
- Model comparison: Compare the performance of the selected models and choose the best-performing model based on the evaluation metrics. You can also perform additional analysis, such as model tuning and cross-validation, to improve the model's performance.

## Conclusion
After conducting the machine learning models and exploratory data analysis (EDA) on the diabetes dataset, I have found the following key insights:

- Based on the evaluation metrics, it can be concluded that the Random Forest Classifier outperformed the Logistic Regression model in predicting the outcome variable (presence of diabetes) for the given dataset. 

- The Glucose level and BMI have a strong positive correlation with the presence of diabetes. This indicates that higher glucose levels and BMI are significant factors in predicting the likelihood of having diabetes.

- The average age of individuals in the dataset was approximately 33 years. This suggests that the dataset primarily consists of relatively young individuals, which could impact the generalizability of the findings to other age groups.

- The number of pregnancies was found to have a mild positive correlation with the presence of diabetes. This suggests that pregnancy history may play a role in diabetes risk, potentially due to hormonal changes and the impact on insulin resistance.

These findings provide valuable insights into the relationships between the predictor variables and the presence of diabetes. By further analyzing and evaluating the models, I can develop more robust predictive models for diabetes diagnosis and gain a better understanding of the risk factors associated with the disease.

## Future Goals
If I had more time and resources, I would like to spend it on exploring amd building other Machine learning models to see which one perform the best for this dataset.
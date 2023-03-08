# Lead-Scoring-Case-Study
This repository contains a logistic regression model that assigns lead scores to potential customers, helping a company increase their conversion rate.

The aim of this project is to build a logistic regression model to assign a lead score to each lead, which can help the company identify hot leads that are most likely to convert into paying customers. The company provided a dataset of around 9000 leads with various attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc. The target variable in this dataset is the "Converted" column, which indicates whether a past lead was converted or not.

The project includes the following components:

- A Jupyter notebook with a well-commented logistic regression model, conversion predictions, and evaluation metrics.
- A Word document with solutions to all the problems presented by the company, based on the logistic regression model.
- A presentation to present the analysis to the chief data scientist of the company, including technical and business aspects.
- A PDF summary report explaining the project's approach and learnings.

## Requirements
- Python 3.7 or higher
- Jupyter Notebook
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- Seaborn
## Data
The dataset provided by the company includes 10 numerical features and 8 categorical features. Some of the categorical features have a level called "Select," which is as good as a null value. The target variable is the "Converted" column, indicating whether a lead was converted or not.

## Approach
The project's approach includes the following steps:

1. Data cleaning and preprocessing: The dataset's missing values, outliers, and categorical features with "Select" levels are handled, and the data is split into training and testing sets.
2. Feature selection: The most important features are selected using univariate and multivariate feature selection techniques.
3. Model building: A logistic regression model is built on the selected features, and the model's performance is evaluated using accuracy, precision, recall, and F1-score.
4. Model evaluation: The model is evaluated using ROC curve and AUC score to measure the model's ability to distinguish between positive and negative classes.
5. Lead scoring: The logistic regression model is used to assign a lead score to each lead, indicating the probability of the lead being converted.

## Results
The logistic regression model's accuracy, precision, recall, and F1-score on the test set were 0.82, 0.77, 0.87, and 0.82, respectively. The ROC curve showed an AUC score of 0.89, indicating that the model could distinguish between positive and negative classes well. The model was used to assign a lead score to each lead, ranging from 0 to 100, based on the probability of the lead being converted. The company can use this lead score to prioritize hot leads that are most likely to convert into paying customers.

## Conclusion
In this project, we learned how to handle missing values, outliers, and categorical features with "Select" levels. We also learned how to select the most important features using univariate and multivariate feature selection techniques. We built a logistic regression model to assign a lead score to each lead, indicating the probability of the lead being converted. We evaluated the model's performance using various metrics, such as accuracy, precision, recall, F1-score, ROC curve, and AUC score. We also learned how to present our analysis to the chief data scientist of the company, including technical and business aspects.

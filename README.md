# CREDIT-CARD
The objective of this project is to use machine learning models to predict fraudulent credit card transactions. We will analyze customer-level data that was gathered and examined during a research collaboration between Worldline and the Machine Learning Group.
Credit card fraud involves any deceitful actions or behaviors aimed at acquiring information without the account holder's authorization for financial gain. The most prevalent method of fraud is skimming, which involves duplicating the information on the card's magnetic strip. Other methods include:

Manipulating or altering genuine cards
Creating counterfeit cards
Using stolen or lost credit cards
Engaging in fraudulent telemarketing


The project pipeline can be summarized in four key steps:

Data Understanding: Load the data and analyze the features to determine which ones are necessary for the final model.
Exploratory Data Analysis (EDA): Conduct univariate and bivariate analyses, and apply feature transformations if needed. For this dataset with Gaussian variables, Z-scaling is not required. However, check for skewness and address it to avoid issues during model building.
Train/Test Split: Split the data into training and testing sets to evaluate model performance on unseen data. Use k-fold cross-validation for validation, ensuring proper representation of the minority class in the test folds by selecting an appropriate k value.
Model Building/Hyperparameter Tuning: Experiment with different models and adjust their hyperparameters to achieve optimal performance. Explore various sampling techniques to enhance the model.
Model Evaluation: Assess the models using suitable metrics. Given the imbalanced nature of the data, prioritize accurately identifying fraudulent transactions over non-fraudulent ones. Choose evaluation metrics that align with this business objective.

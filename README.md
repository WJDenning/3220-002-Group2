# 3220-002-Group2
For the Fundamentals of Data Science Group Project
Uses the [Poisonous Mushrooms Competition Data Set](https://www.kaggle.com/competitions/playground-series-s4e8/overview) from Kaggle

## Group Members
- Collin Chappell
- Will Denning
- Evan Mcintyre
- Alexander Redd
- Travis Schowen
- 
## About the Dataset
The goal for this project is to predict whether a mushroom is poisonous or edible using its physical and categorical features. To successfully complete this, a binary machine learning model will be developed to accurately classify mushrooms into the two categories. This project is based on the Kaggle competition Binary Prediction of Poisonous Mushrooms. The dataset for this problem was synthetically generated from a deep learning model trained on the UCI Mushroom dataset, creating slight differences from the original data. The model’s performance might be evaluated on accuracy, precision, recall, F1-Score, ROC, and log loss. These performance measures will be used to show how accurately the model can differentiate between edible and poisonous mushrooms, as well as how confident and reliable its predictions are.  

Classifying mushrooms as either edible or poisonous is important in the real world for public safety and health, most notably for foragers or biologists. If a mushroom is incorrectly classified as safe, there could be deadly consequences, so accuracy is essential. With a better solution to this problem, mushrooms in the wild could be much safer, as it would allow for more reliable recognition of which are poisonous and which are edible. The original mushroom dataset from UC Irvine has been used in data science and machine learning projects.  

## Cleaning the Data

#### Removing Noise
Some of the features within the given test data set contain noisy values. For example, where a categorical value is expected, a numerical one is found within a few rows. To get rid of noise, we take all categorical features and replace any noisy value (a value which appears less than 100 times within the 3 million entries) with N/A.
The visualization and R script for this can be found within the noise.Rmd and noise.pdf files. 

#### Removing Outliers
Outliers for the numerical values were identified by looking at a boxplot and using the whiskers to handle them by removal. We loaded the data using R and used it to clean and visualize the dataset.  We used R’s native features to summarize, analyze and clean the data including boxplots to find outliers. 
The visualization and R script for this can be found within outlier.Rmd and outlier.pdf files.

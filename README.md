VACCINATION TREND PREDICTOR

what is mostly likely to influence vaccination rates in future?

The aim of this project is to develop a model that will provide guidance to the National Vaccination Advisory committee in understanding how people’s backgrounds, opinions, and health behaviors are related to their personal vaccination patterns and to predict vaccination patterns.

Data used : National 2009 H1N1 Flu Survey.

Data Preparation
1. Loading data
2. Exploring Datasets.

Exploratory Data Analysis
Data was analyzed by exploring how different features were related to the target variable(seasonal vaccine)

Modelling
All non_numeric columns were dropped because the project is a binary classification problem and string variables could not be encoded as binary.
Missing values were imputed using the k-Nearest Neighbor Imputation.
Model was trained using a split size of 75/25%.

Logistic Regression model yielded a model accuracy of 79.1% in comparison to other binary classifier models.

                  	            Accuracy	Precision	Recall
Logistic Regression                 0.791373	0.740298	0.795068

Support Vector Machines             	0.787030	0.730918	0.792982

Decision Trees              	0.696570	0.690815	0.666251

Random Forest               	0.783885	0.769082	0.765369

Naive Bayes                 	0.697619	0.806274	0.637107

K-Nearest Neighbor          	0.736109	0.688228	0.727273


Tech Stack

Python

Pandas

Matplotlib

Seaborn

Scikit-Learn


Conclusion

The model will predict 79 samples correct.

The number of people who received the seasonal vaccine is lower than those who didn't receive the vaccine.

Most of those who received the vaccine were male.

Most of the health workers received the vaccine.

The older people(65 Years and above) received the vaccine in high numbers compared to the young people.

The number of those who received the vaccination through reccomendation by a doctor was also high.

People with chronic medical conditions didnot receive the vaccine.

People who felt that the seasonal vaccine was very effective received the vaccine.

Factors like Education level, employment status and race rarely affected the vaccination rate.


Reccommendation

Vaccinate older people because they are willing.

Educate people on the importance of vaccination(doctors'reccomendation helps).
# Heart Disease Analysis

Midterm project for STA160 at UC Davis

Research Question(s):
- Is it appropriate to classify observations into heart-disease/no-heart disease? I.e. are these two classes singificantly different?
- Which variables are significant in predicting the response (heart-disease/no heart-disease) ? 
- Which algorithm predicts heart disease with the highest accuracy?

EDA:
- Summary statistics (count, mean, sd, min, quartiles, max)
- Histograms of significant variables
- Contingency Tables + Shannon Entropy
- Hierarchical clustering

Analysis:
- Independence test 
   -  parametric chi-sq test for independence 
- K-groups Kruskal-Wallis Test

Prediction: 
- LDA
- Logistic Regression
- SVM
- Naive Bayes
- Decision Tree


How to navigate this repository:
- `Notebooks` contains all jupyter notebooks used for EDA, Statistical analysis, and Prediction scripting.
- `Visualizations` contains some additional jupyter notebooks containing EDA visualizations.
- `data` contains the cleaned data sourced from kaggle.com (https://www.kaggle.com/datasets/alexteboul/heart-disease-health-indicators-dataset)
- `Analysis_of_Heart_Disease` is a report containing EDA interpretations, statistical analysis results, prediction procedures and final conclusions extracted from our data. 

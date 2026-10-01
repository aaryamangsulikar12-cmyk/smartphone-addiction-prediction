## Smartphone Addiction Probability Prediction
A machine learning project built for a Kaggle competition to predict smartphone addiction risk using user demographics, academic impact, 
and daily usage habits (~691K training rows, ~296K test rows).

## Project Overview 
This project explores different machine learning approaches for predicting smartphone addiction probability. 
The workflow includes exploratory data analysis, data preprocessing, model training, and evaluation using ROC-AUC and Log Loss.
The project follows an iterative approach, starting with a Logistic Regression baseline and then experimenting with gradient boosting models
to improve predictive performance.

## Workflow
1. Data loading and exploration
2. Exploratory Data Analysis (EDA)
3. Data preprocessing
4. Model training
5. Probability prediction
6. Model evaluation using ROC-AUC and Log Loss
   
## Models Used
Logistic Regression
LightGBM
XGBoost

## Model Performance
Model	              |ROC-AUC	        |Log Loss
Logistic Regression	|0.91075	        |0.39350
LightGBM	          |0.95940	        |0.23446
XGBoost	            |0.96028	        |0.23205

Among the evaluated models, XGBoost achieved the highest ROC-AUC and the lowest Log Loss.

## Evaluation Metrics
### ROC-AUC
ROC-AUC measures how well the model distinguishes between the target classes across different classification thresholds. 
A higher value indicates better ranking/discrimination performance.
### Log Loss
Log Loss evaluates the quality of predicted probabilities. 
Lower values indicate better-calibrated probability predictions and penalize confident incorrect predictions more heavily.

## Kaggle Competition
This project was developed as part of a Kaggle competition. The notebooks document the experimentation process and progression 
across different machine learning models.

## Key Takeaway
The project demonstrates an iterative machine learning workflow, where a simple baseline model was followed by more advanced 
gradient boosting techniques and evaluated using probability-based performance metrics.

### Repository Structure
smartphone-addiction-prediction/
│
├── PSA-logistic.ipynb
├── PSA-LightGBM.ipynb
├── PSA-XGBoost.ipynb
└── README.md

## Dataset
The dataset was provided through the Kaggle competition Predicting Smartphone Addiction — Playground Series S6E8.
The competition dataset is not included in this repository because the competition rules restrict participants from publishing, redistributing, or making the Competition Data available to people who have not agreed to the competition rules.
To reproduce the analysis, obtain the competition data directly through Kaggle after joining the competition.
The notebooks in this repository contain the data preprocessing, exploratory analysis, model training, and evaluation workflow.

## Author
Aarya Mangsulikar
MSc Data Science

# Datathon-2

**See Datathon2-Final.ipynb for the final version of our codes!**

## Research questions

Can we predict death events using characteristics of heart failure patients?

## Analysis Plan

### Features: 
* Covariates: age, sex, ejection fraction, anemia, hypertension, CK, serum creatinine, sodium
* Outcome: death
* Model: KNN/logistic

### Data Processing 
* Data cleaning and exploration
* Remove observations with missing values/unknowns

### Training and test data
* Feature selection: VIF, clinical significance
* Visualization

### Modelling
* Logistic regression model: non-weighted and weighted
* KNN: choose optimal K using error rate
* Compare the two/three models

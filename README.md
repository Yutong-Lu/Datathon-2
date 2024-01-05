# Predictive Modeling for Heart Failure Mortality: Logistic Regression and KNN Analysis
## Authors: Yutong Lu, Feifan Xiang, Man Xue

**Datathon 2, CHL5230, Dalla Lana School of Public Health**

### Introduction
- Aimed to predict heart failure mortality using logistic regression and K-nearest neighbor (KNN) models.
- Based on previous research, identified predictors like age, ejection fraction, and clinical risk factors.

### Data Engineering Process
- Imported mortality dataset and handled missing values.
- Selected features based on clinical relevance, addressed multicollinearity, and normalized data.
- Split data into 80% training set and 20% testing set for modeling.

### Analysis
- Utilized logistic regression and KNN for mortality prediction due to labeled outcome data.
- Used L2 penalty for logistic regression, adjusting for class imbalance with weighted logistic regression.
- Determined the optimal K (K=5) for the KNN model through error rate analysis.
- Evaluated model performance using classification reports and confusion matrices.

### Findings
- Patients were middle-aged, with features like age and ejection fraction strongly associated with heart failure mortality.
- Logistic regression achieved 65% accuracy, with weighted logistic regression providing better recall for death events (40% higher).
- KNN (K=5) showed 65% accuracy, higher precision for death events, but lower recall (20%) for predicting actual deaths.

### Conclusion
- Models have potential for identifying patients needing enhanced care but should supplement clinical decisions, not replace them.
- Both logistic regression and KNN models showed limitations in recognizing actual death events, suggesting caution in clinical reliance.

### Contributions
- Yutong Lu: KNN coding, analysis, conclusions, slides preparation
- Feifan Xiang: Logistic regression coding, data engineering, analysis, slides preparation
- Xue Man: Logistic regression coding, introduction, findings, slides preparation

### Links
- [Presentation Slides](https://tinyurl.com/27z9sdpr)

For a detailed understanding, kindly refer to the full report available in the provided GitHub repository.


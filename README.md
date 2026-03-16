## Disease Outbreak Prediction using Machine Learning

**Thesis project — MSc Data Science & AI**

### Problem
Predicting malaria and dengue outbreaks using integrated 
epidemiological, climate, mobility, and healthcare data.

### Models Compared
| Model        | RMSE | R²   | MAPE  |
|--------------|------|------|-------|
| Neural Network | 15.2 | 0.78 | 12.4% |
| ARIMA (2,1,2)  | 18.5 | 0.70 | 14.2% |
| Decision Tree  | 20.8 | 0.62 | 18.9% |

### Key Findings
- Neural Network outperformed baseline by 27% on RMSE
- Temperature (32%) and precipitation (24%) were 
  strongest predictors
- Applied SMOTE, PCA, and temporal aggregation 
  for data preprocessing

### Tech Stack
Python, Pandas, Scikit-learn, TensorFlow, Statsmodels, 
Matplotlib, Jupyter Notebooks

### Published
DOI: 10.13140/RG.2.2.35607.23208

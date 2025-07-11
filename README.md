# Wine Quality 
**Predicting Wine Quality using Machine Learning methods**
As part of my advanced analytics coursework, I tackled the classic Wine Quality dataset from the UCI Machine Learning Repository, applying modern supervised learning techniques to predict wine quality based on physicochemical properties.

Project Highlights:
Objective: Classify wines as high or low quality using chemical features like acidity, sugar, sulphates, and alcohol content.
Dataset: 6,497 samples (red & white wines), with features such as pH, residual sugar, alcohol, and sulphur dioxide concentrations.

Modelling Approaches:
- Lasso Regression for feature selection and multicollinearity mitigation
- Random Forest for capturing non-linear relationships and robust prediction

Key Insights & Results:
Random Forest outperformed Lasso Regression:
- Accuracy: 82.5% (Random Forest) vs. 73.7% (Lasso)
- Sensitivity: 74.3% (RF) vs. 55.0% (Lasso)
- Specificity: 87.3% (RF) vs. 84.4% (Lasso)
Top Predictors: Alcohol, sulphates, and volatile acidity were the most influential features in determining wine quality.
White wines showed a higher proportion of high-quality ratings compared to red wines.

Visuals Used:
- Boxplots of alcohol, residual sugar, and volatile acidity by wine type
- Variable importance plot (Random Forest)
- Partial dependence plots for key predictors
- Confusion matrices and accuracy comparison tables

Takeaways:
- Machine learning models can automate and objectify wine quality assessment, reducing reliance on subjective sensory tests.
- Random Forest models are highly effective for quality classification, while Lasso Regression aids interpretability and feature selection.
- Alcohol content remains the strongest single predictor of wine quality.

This project deepened my expertise in data cleaning, EDA, model tuning, and validation—core skills for any data scientist.

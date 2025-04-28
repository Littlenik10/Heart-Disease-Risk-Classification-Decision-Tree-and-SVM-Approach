# Heart Disease Classification using Machine Learning

This project builds and compares two machine learning models — Decision Tree and Support Vector Machine (SVM) — to classify the presence of heart disease using clinical data.

## Project Overview 
- Used the heart disease dataset (302 samples, 14 features).
- Conducted data cleaning, feature selection, and exploratory data analysis (EDA).
- Built, tuned, and evaluated Decision Tree and SVM models.
- Compared models based on accuracy, precision, recall, F1-score, and ROC-AUC.

## Key Results
- SVM achieved better performance in terms of testing accuracy (82.89%), precision, recall, F1-score, and ROC-AUC.
- Decision Tree showed higher training accuracy but was more prone to overfitting.

## Tools and Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Lessons Learned
- Importance of feature selection and scaling.
- Handling overfitting using hyperparameter tuning.
- Focus on minimizing false negatives in healthcare-related machine learning tasks.

## Conclusion
The Support Vector Machine (SVM) model was selected as the better model for heart disease prediction due to its higher generalization capability and stronger performance across evaluation metrics.

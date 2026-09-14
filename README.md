# Wine Quality Prediction

## Project Overview
This project predicts wine quality categories using machine learning classification algorithms based on physicochemical properties.

Models used:
- Random Forest Classifier
- SGD Classifier
- Support Vector Classifier (SVC)

## Dataset
`WineQT.csv` contains 1,143 rows and 13 columns, including 11 physicochemical features, an `Id` identifier, and the `quality` target. There are no missing values. The `Id` column was removed before model training.

## Feature Engineering
Wine quality scores were grouped into three categories:
- Low: 3–4
- Medium: 5–6
- High: 7–8

This reduced the number of highly imbalanced individual quality classes while retaining meaningful quality information.

## Data Preparation
An 80/20 stratified train-test split was used to preserve class proportions. StandardScaler was applied to the SGD and SVC models.

## Model Results

| Model | Accuracy | Main Strength |
|---|---:|---|
| Random Forest | **86%** | Best overall accuracy |
| SVC | 65% | Better minority-class detection |
| SGD Classifier | 64% | Better minority-class recall |

Random Forest achieved approximately 86% accuracy and 84% weighted F1-score. However, it struggled to identify the Low-quality class. SVC and SGD achieved approximately 0.75 recall for Low-quality wines.

## Evaluation
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrices

Because the dataset is imbalanced, macro F1-score and class-specific recall were also considered.

## Feature Importance
Random Forest feature importance was used to identify the physicochemical properties that contributed most to predictions.

## Conclusion
Random Forest was the strongest overall model when general prediction accuracy was the main objective. However, if identifying rare Low-quality wines is more important, SVC or SGD may be preferable because they detected the minority class more effectively.

## Future Improvements
- Hyperparameter tuning
- Cross-validation
- Advanced class-balancing techniques
- Collecting more minority-class samples
- Testing additional classification algorithms
- Feature selection and engineering
- Optimizing for macro F1-score
- Building a web application

## Technologies Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, and Jupyter Notebook.

## Project Structure
```text
Wine-Quality-Prediction/
├── WineQT.csv
├── Wine_Quality_Prediction.ipynb
├── README.md
└── images/
```

## Skills Demonstrated
Data preprocessing, EDA, visualization, feature engineering, class imbalance handling, stratified splitting, feature scaling, classification, model evaluation, confusion matrix analysis, feature importance, and model comparison.

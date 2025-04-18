# Lung-Cancer-Prediction

This project aims to predict lung cancer survival using patient diagnosis data. The dataset contains various features related to patient demographics, treatment history, and cancer stage.

## Dataset

The dataset used in this project is `dataset_med.csv`, which includes the following columns:

- **age**: Age of the patient
- **bmi**: Body Mass Index
- **cholesterol_level**: Cholesterol level of the patient
- **cancer_stage**: Stage of cancer (Stage I, II, III, IV)
- **treatment_type**: Type of treatment received (Surgery, Chemotherapy, Radiation, Combined)
- **survived**: Survival status (1 = Survived, 0 = Not Survived)

## Data Visualization

The project includes various visualizations to understand the data better, including:

- Distribution of the target variable (Survival)
- Histograms of age, BMI, and cholesterol levels
- Box plots for age, BMI, and cholesterol levels
- Heatmap of feature correlations

## Machine Learning Models

The following machine learning models are implemented in this project:

- Logistic Regression
- XGBoost Classifier
- Random Forest Classifier

## Usage

1. Clone the repository.
2. Install the required packages using:
   ```
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook `lung_cancer.ipynb` to execute the analysis and model training.

## Output Images

The output images generated from the notebook will be included here.

### Feature Correlation Heatmap
![Feature Correlation Heatmap](https://github.com/user-attachments/assets/f6969210-23af-43ac-870b-8c12e2ff5dad)

### Random Forest Classifier
- **Accuracy**: 0.7796
- **Classification Report**:
```
              precision    recall  f1-score   support

         0.0       0.78      1.00      0.88    104100
         1.0       0.14      0.00      0.00     29400

    accuracy                           0.78    133500
   macro avg       0.46      0.50      0.44    133500
weighted avg       0.64      0.78      0.68    133500
```
- **Confusion Matrix**:
```
[[104075     25]
 [ 29396      4]]
```

### XGBoost Classifier
- **Accuracy**: 0.7797003745318352
- **Classification Report**:
```
              precision    recall  f1-score   support

         0.0       0.78      1.00      0.88    104100
         1.0       0.25      0.00      0.00     29400

    accuracy                           0.78    133500
   macro avg       0.51      0.50      0.44    133500
weighted avg       0.66      0.78      0.68    133500
```
-**Confusion Matrix**:
```
[[104085     15]
 [ 29395      5]]
```


## License

This project is licensed under the MIT License.

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

###Feature Correlation Heatmap
![Feature Correlation Heatmap](https://github.com/user-attachments/assets/f6969210-23af-43ac-870b-8c12e2ff5dad)

## License

This project is licensed under the MIT License.

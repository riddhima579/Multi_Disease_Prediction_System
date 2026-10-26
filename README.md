# Multi-Disease Prediction System Using Machine Learning

## Overview
The Multi-Disease Prediction System is a machine learning project developed using Python to predict the likelihood of three chronic diseases: Diabetes, Heart Disease, and Chronic Kidney Disease (CKD).

The project uses separate machine learning models for each disease and follows a structured workflow involving data preprocessing, feature preparation, model training, and evaluation.

## Objectives
- Develop separate prediction models for three diseases.
- Clean and preprocess medical datasets.
- Handle missing values and encode categorical features where required.
- Apply feature scaling to suitable models.
- Train and evaluate machine learning classifiers.
- Compare model performance using testing accuracy.

## Diseases and Algorithms

| Disease | Algorithm | Testing Accuracy |
|---|---|---:|
| Diabetes | Support Vector Machine (SVM), Linear Kernel | 77.27% |
| Heart Disease | Logistic Regression | 88.52% |
| Chronic Kidney Disease | Random Forest Classifier | 98.75% |

For heart disease, Random Forest was also evaluated, achieving a testing accuracy of 86.88%.

## Datasets
The project uses three publicly available datasets:

- **Diabetes:** Pima Indians Diabetes Dataset
- **Heart Disease:** UCI Cleveland Heart Disease Dataset
- **Kidney Disease:** Chronic Kidney Disease Dataset

## Technologies Used
- Python
- Google Colab
- Pandas and NumPy
- Scikit-learn
- Matplotlib and Seaborn

## Methodology
1. Load and explore the datasets.
2. Clean the data and handle missing values where required.
3. Separate input features and target variables.
4. Split the data into training and testing sets.
5. Apply feature scaling or categorical encoding as appropriate.
6. Train the disease-specific machine learning models.
7. Evaluate the models using training and testing accuracy.
8. Test predictions using sample patient inputs.

## Project Structure

```text
Multi_Disease_Prediction_System/
├── README.md
├── .gitignore
└── Multiple_Disease_Prediction.ipynb
```

The notebook uses external dataset files. These must be made available in the Google Colab runtime using the filenames and paths expected by the notebook.

## How to Run
1. Open `Multiple_Disease_Prediction.ipynb` in Google Colab.
2. Upload or make the required dataset files available in the runtime.
3. Check that the dataset filenames and file paths match those used in the notebook.
4. Run the notebook cells in order to preprocess the data, train the models, and view the evaluation results.

## Limitations
- The models were evaluated on relatively small benchmark datasets.
- The reported results primarily use accuracy and do not establish clinical reliability.
- The models have not been validated on an independent clinical dataset.
- Predictions may not generalize to all patient populations.

## Future Scope
- Evaluate precision, recall, F1-score, and confusion matrices.
- Test models on larger, independent datasets.
- Add prediction confidence information and input validation.
- Develop a unified web or mobile application.
- Explore explainable AI techniques to improve model interpretability.

## Disclaimer
This project is intended for educational and research purposes only. Its predictions are not medical diagnoses and must not be used as a substitute for professional medical advice or clinical testing.

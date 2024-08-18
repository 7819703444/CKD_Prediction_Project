
# Predicting Chronic Kidney Disease Onset Using Machine Learning

## Overview
This project aims to predict the onset of Chronic Kidney Disease (CKD) using machine learning models. The dataset used in this project consists of electronic health records (EHRs) from 491 patients at Tawam Hospital, Abu Dhabi. By leveraging Logistic Regression, Random Forest, and Neural Networks, this project explores which model best predicts CKD onset and identifies key clinical features contributing to the prediction.

## Project Objectives
- **Data Exploration:** Perform Exploratory Data Analysis (EDA) to understand the dataset and identify any patterns or anomalies.
- **Data Preprocessing:** Scale the features and address class imbalance using SMOTE (Synthetic Minority Over-sampling Technique).
- **Model Building:** Train and compare the performance of three machine learning models: Logistic Regression, Random Forest, and Neural Networks.
- **Model Evaluation:** Evaluate the models using metrics like accuracy and AUC-ROC to determine the most effective model for predicting CKD.
- **Feature Importance:** Analyze the importance of various features in predicting CKD onset.

## How to Run the Notebook
1. **Install Dependencies:**
   Ensure you have the required libraries installed. You can install them using pip:
   ```bash
   pip install pandas numpy scikit-learn imblearn matplotlib seaborn
   ```

2. **Run the Jupyter Notebook:**
   Open the `CKD_Prediction_Project.ipynb` file in Jupyter Notebook or JupyterLab and run the cells in sequence.

3. **View Results:**
   The notebook includes code cells for data loading, preprocessing, model training, and evaluation. Results, including model performance metrics and feature importance plots, will be displayed as you execute the cells.

## Results
- **Logistic Regression** achieved the highest AUC-ROC score, making it the most effective model for CKD prediction in this dataset.
- **Random Forest** provided valuable insights into feature importance, with eGFRBaseline and CreatinineBaseline emerging as the most significant predictors.
- **Neural Network** showed good performance but was slightly outperformed by Logistic Regression in terms of AUC-ROC.

## Future Work
- Expand the dataset to include more diverse populations and longer follow-up periods.
- Further tune the hyperparameters or explore advanced techniques like deep learning to improve model performance.
- Consider integrating these predictive models into clinical decision support systems to assist healthcare providers in real-time.

## GitHub Repository
The full project, including the Jupyter notebook and any related files, is available in this repository.

## Contact
For any questions or further discussion, please feel free to reach out via GitHub or email.

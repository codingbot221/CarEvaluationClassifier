# CarEvaluationClassifier

This project implements a machine learning classifier to evaluate car acceptability using the UCI Car Evaluation Dataset. It explores, trains, and compares several classification algorithms to predict how acceptable a car is based on key automotive features.

## Project Overview 

- Dataset: UCI Car Evaluation Dataset  
  - Features: `buying`, `maint`, `doors`, `persons`, `lug_boot`, `safety`  
  - Target labels: `unacc`, `acc`, `good`, `vgood`
- Objective: Predict car acceptability using various machine learning models
- Workflow:
  - Perform exploratory data analysis (EDA)
  - Preprocess categorical features using label encoding
  - Train and evaluate models: Decision Tree, Random Forest, Logistic Regression, K-Nearest Neighbors, Multi-layer Perceptron
  - Apply SMOTE to handle class imbalance
  - Evaluate models using classification reports and confusion matrices
  - Build a simple user interface using Gradio
 
## Technologies Used    
 ----------------------------------------------------
| Category              | Tools                     |
|-----------------------|---------------------------|       
| Programming Language  | Python                    |
| Data Analysis         | pandas, numpy             |
| Visualization         | matplotlib, seaborn       |
| Machine Learning      | scikit-learn              |
| Class Imbalance       | imbalanced-learn (SMOTE)  |
| Optional Web App      | Streamlit or Flask        |
 ---------------------------------------------------
## Installation

#  1.Clone the repository
  
   `git clone https://github.com/codingbot221/CarEvaluationClassifier.git` <br>
` cd CarEvaluationClassifier`  <br>
# 2.Usage  
   Run the notebook  <br>
   Open the Jupyter notebook to view the analysis, model training, and evaluation:  <br>
   jupyter notebook CarEvaluationClassifier.ipynb <br>

# 3.Run the Gradio app 
If you want to try the live model via the user interface:  <br>
python gradio_app.py  <br>
Then open the automatically generated link in your browser.  <br>

## ModelPerformance
 Final model performance on the test set is summarized below:  <br>

 _ __ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ 
| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| 0     | 1.00      | 1.00   | 1.00     | 69      |
| 1     | 1.00      | 1.00   | 1.00     | 15      |
| 2     | 1.00      | 1.00   | 1.00     | 251     |
| 3     | 1.00      | 1.00   | 1.00     | 11      |
- - - - - - - - - - - - - - - - - - - -- - -  - - -
**Overall Metrics**
 _ _ _ _ _ _ _ _ _ _ _ _
| Metric        | Value |
|---------------|-------|
| Accuracy      | 1.00  |
| Macro Avg     | 1.00  |
| Weighted Avg  | 1.00  |
| Total Support | 346   |
- - - - - - - - - - - - -

Accuracy: 100%  <br>
 
Perfect classification across all classes  <br>

Demonstrates excellent generalization from the model  <br>

## GradioUI

https://github.com/user-attachments/assets/ab387b2f-1e6b-4960-bcc5-3fdd30b28446




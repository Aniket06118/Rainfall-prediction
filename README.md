##  Project Description
This project uses the **Rain in Australia** dataset to build models that predict whether it will rain tomorrow
We preprocess the data, split it into training/validation/test sets, and train three different classifiers: Logistic Regression, Decision Tree, and Random Forest.

---

##  Dataset Info

- Dataset: Rain in Australia (Weather Dataset – Rattle package)
- Source: https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package 
- Description:  Includes features like rainfall, humidity, wind, temperature, etc. Target variable is RainTomorrow
- 
##  Workflow

1. **Preprocessing**  
   - Load raw dataset  
   - Handle missing values, encode categorical columns, convert data types, etc.  
   - Split into `train`, `validation`, `test`

2. **Model Training**  
   - Train Logistic Regression, Decision Tree, Random Forest on training data  
   - Tune hyperparameters (where applicable) using validation set  

3. **Evaluation and Comparison**  
   - Evaluate models on validation set  
   - Generate metrics: accuracy, precision, recall, F1-score  
     



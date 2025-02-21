Diabetes Datasets (Rashid, 2020)
This datasets focuses on predicting diabetes classes (No Diabetes, Pre-Diabetes, Diabetes) using machine learning models.
Features includes: 
  ID: Unique identifier for each patient
  No_Pation: Number of partitions
  Gender: Gender of the patient (Male, Female)
  AGE: Age of the patient
  Urea, Cr, HbA1c, Chol, TG, HDL, LDL, VLDL, BMI: Health indicators
  CLASS: Diabetes class (No Diabetes, Pre-Diabetes, Diabetes)
What was done:
1. EDA - cleaning for unique values in Gender and Class
2. Feature Engineering - added Age range with +10 per bracket
3. Visualization - shows the Age bracket and Gender with different Diabetes Class
4. Data Split - Split data to 80% Train and 20% Test. Used Label encoding to convert categorical into numerical features and normalized the data
5. Model Training - used k-folds cross-validation, and XGB model gives the best accuracy
6. Model PRediction - XGB gives the highest accuracy on Train data, but the Random Forest Classifier gives the highest in the Test Data
 

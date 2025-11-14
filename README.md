# CropYield-Prediction
This project uses machine learning to predict crop yield based on factors like rainfall, temperature, soil type, and fertilizer usage. The model analyzes historical data to estimate how much crop can be produced. It helps in planning, resource management, and improving agricultural decisions.

Features
Predicts crop yield using ML models
Uses real agricultural parameters
Supports multiple crops and regions
Easy to train and test
Helps in planning and resource optimization

Python
Scikit-learn
Pandas
NumPy
Matplotlib / Seaborn
Jupyter Notebook

Machine Learning Models Used
Random Forest Regressor

Datasets used
Crop  
Crop_Year       
Season  State    
Area  Production
Annual_Rainfall  
Fertilizer  Pesticide        
Yield  


Steps / Workflow
Load and clean the dataset
Perform EDA (visualizations, correlations)
Encode categorical values
Split data into train & test
Train ML models
Evaluate using RMSE, MAE, R²
Predict crop yield for new input

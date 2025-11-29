# house-price-prediction (ML Pipeline)

This project is a complete end-to-end regression pipeline built using Python and Scikit-Learn.  
It covers everything from data loading -> preprocessing -> pipeline creation -> model training -> saving model -> inference on new data.  

It uses the California Housing Dataset, focusing on predicting _median_house_value._

---

## Project Structure

├── housing.csv  
├── input.csv   
├── output.csv  
│  
├── model.pkl  
├── pipeline.pkl  
│  
├── main.py  

---

## Installation

- Using pip:  
python -m pip install pandas numpy scikit-learn joblib
- Using conda:  
conda install pandas numpy scikit-learn joblib

---

## Running the Project

- 1 - Train the Model (first run) - Creates model.pkl, pipeline.pkl, and input.csv.

python main.py
  
- 2 - Run Inference (after training) - Reads input.csv -> predicts values -> saves output.csv.

python main.py

---

## Tech Stack / Libraries Used

Python  
Pandas
NumPy
Scikit-Learn –  
--Pipeline, ColumnTransformer  
--SimpleImputer, StandardScaler, OneHotEncoder  
--LinearRegression, DecisionTreeRegressor, RandomForestRegressor    
Joblib – saving/loading model & pipeline  
Jupyter Notebook  


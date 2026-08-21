# Nigeria Crop Yield Predictor 🌾

Predicts maize/rice/sorghum yield 60 days before harvest using Weather, Soil, and Pesticide data.

### Problem
70% of Nigerian farmers have no access to yield forecasts. Banks can't risk-score loans.

### Solution
ML model that takes: Rainfall, Temp, Soil N, pH, Pesticide → Predicts yield in tons/ha + gives recommendations.

### Tech Stack
Python, Pandas, Scikit-learn, SDV for synthetic data, Streamlit, NASA POWER API

### How to Run
1. pip install -r requirements.txt
2. python generate_data.py
3. python train_model.py  
4. streamlit run app.py

### Key Results
- R2 Score: 0.78 on synthetic data
- Top Features: Rainfall, Soil Nitrogen, Pesticide Use
- Demo: [Streamlit Link Coming]

### Impact
Helps banks, insurers, and cooperatives make data-driven decisions for 38M Nigerian farmers.
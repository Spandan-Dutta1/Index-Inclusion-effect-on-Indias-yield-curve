# Indian Sovereign Yield Curve Deformation : Following JP Morgan GBI-EM Index Inclusion
## Research Question
Did the mechanical inclusion of Indian G-Secs in the JP Morgan 
GBI-EM index in June 2024 causally deform the sovereign yield 
curve term structure?
## Methodology
- Instrumental Variable (2SLS) estimation
- JP Morgan index weight schedule used as exogenous instrument
- Multinomial Logit for yield curve regime classification
- XGBoost + SHAP for ML-driven regime prediction
## Data Sources
- RBI DBIE: G-Sec yields and FPI ownership
- FRED: US 10Y, VIX
## Tools
Python | pandas | statsmodels | linearmodels | 
scikit-learn | xgboost | shap

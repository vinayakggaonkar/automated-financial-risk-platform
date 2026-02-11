Automated Financial Risk Scoring Platform (Machine Learning + LLM)

Overview



An end-to-end financial risk classification system built using real SEC financial statement data.

The platform classifies companies into Low, Medium, and High financial risk categories using engineered financial ratios and XGBoost.



The system integrates SHAP explainability and LLM-generated business summaries to provide transparent, stakeholder-ready risk explanations.



Key Features



Real SEC Financial Statement Data ingestion (2M+ records processed)



Financial ratio engineering (liquidity, leverage, profitability, cash flow metrics)



Composite financial stress score construction



Multi-class XGBoost classification



5-fold cross-validation for robustness



SHAP global and per-company explainability



Automated LLM-based financial risk narratives



Tech Stack



Python



Pandas / NumPy



Scikit-learn



XGBoost



SHAP



OpenAI API



Matplotlib / Seaborn



Model Performance



Accuracy: ~96%



ROC-AUC (multi-class OVR): ~0.997



Balanced class distribution



Stable 5-fold cross-validation (mean ~95%)



Model Architecture



Financial Data → Feature Engineering → Risk Score Construction →

XGBoost Classification → SHAP Explainability →

LLM Risk Narrative Generation



Business Impact



Reduces manual credit risk evaluation effort



Provides explainable, auditable risk classification



Enables faster, data-driven decision support



Demonstrates integration of ML + LLM in financial analytics



Project Structure

financial-risk-platform/

│

├── data/processed/

├── notebooks/

├── models/

├── src/

├── requirements.txt

├── README.md

└── .gitignore



Future Improvements



Replace synthetic risk labels with real default data



Add time-series financial trend features



Incorporate macroeconomic indicators



Deploy as API or Streamlit application


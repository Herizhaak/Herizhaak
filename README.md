## Hi, I'm Isaac Hiri

**Data Scientist · ML model evaluation · Health data**
Olympia, WA · Open to remote, hybrid and on-site roles

I build machine-learning models and, just as importantly, check whether they actually work. I start with baselines, keep pipelines leakage-safe, report confidence intervals, check calibration and subgroups, and write up the limitations honestly. Most of my projects use health data. I also teach Python, machine learning and Azure fundamentals to students entering the field.

### Featured projects

| Project | What it shows |
|---|---|
| [**LLM Evaluation Harness**](https://github.com/Herizhaak/llm-eval-harness) | Three small open LLMs (360M–1.5B) on PubMedQA, CPU only: strict answer parsing, bootstrap CIs, McNemar/Holm paired tests and calibration. The best model beats "always yes" by 10 points, which is not significant at n = 120. An LLM judge was validated against known answers and control inputs, and it failed (κ = 0.18). |
| [**Hospital 30-Day Readmission**](https://github.com/Herizhaak/hospital-readmission-30day) | 99k real US hospital encounters, split by patient so no patient appears in both train and test. ROC-AUC 0.67 [0.66, 0.69]. Includes calibration, a threshold set by intervention capacity, and subgroup checks by age, race and payer. |
| [**Diabetes Risk API**](https://github.com/Herizhaak/diabetes-risk-api) | Serves the NHANES no-blood-test diabetes model with FastAPI: validated questionnaire inputs, ADA score alongside the model, versioned model card, Prometheus metrics, prediction logging and a PSI/KS drift endpoint. 62 tests, Docker, CI. |
| [**Diabetes Screening Without a Blood Test**](https://github.com/Herizhaak/diabetes_pred) | 8,064 US adults from CDC NHANES. A no-lab logistic model beats the ADA risk test (ROC-AUC 0.83 vs. 0.79) and flags 8 points fewer people at the same sensitivity. Survey-weighted prevalence, calibration and subgroup checks. |
| [**Heart Failure Mortality Risk**](https://github.com/Herizhaak/heart_disease_pred) | 299 patients, repeated and nested CV, bootstrap CIs, ROC-AUC 0.79 [0.74, 0.85]. Shows that the follow-up-time column leaks the outcome (AUC jumps to 0.91 with it) and that the model is only modestly better than a two-variable clinical baseline. |
| [**US Retail Sales Analytics**](https://github.com/Herizhaak/superstore_forecast) | 34 years of Census retail data: DuckDB SQL (e-commerce from 0.9% to 16% of sales, the 2020 COVID shock), a Plotly dashboard, and a rolling-origin forecast backtest where SARIMA is best (1.4% MAPE vs. 3.1% for seasonal naive). |

### Tools I use

- **Python and ML:** pandas, NumPy, scikit-learn, XGBoost, imbalanced-learn, statsmodels, Hugging Face Transformers
- **Evaluation:** cross-validation, PR-AUC / ROC-AUC, calibration, bootstrap confidence intervals, threshold selection, subgroup analysis, LLM-as-judge, inter-rater agreement (Cohen's κ)
- **Engineering:** FastAPI, Pydantic, pytest, GitHub Actions, Docker, Prometheus metrics, SQLite
- **Data and BI:** SQL (DuckDB), Power BI, Excel
- **Visualisation:** Matplotlib, Seaborn, Plotly
- **Cloud:** Microsoft Certified: Azure Fundamentals (AZ-900)

### Contact

[LinkedIn](https://www.linkedin.com/in/isaachiri) · [Kaggle](https://www.kaggle.com/isaachiri)

## Hi, I'm Isaac Hiri

**Data Scientist · ML model evaluation · Health data**
Olympia, WA · Open to remote, hybrid and on-site roles

I build machine-learning models and, just as importantly, check whether they actually work. I start with baselines, keep pipelines leakage-safe, report confidence intervals, check calibration and subgroups, and write up the limitations honestly. Most of my projects use health data. I also teach Python, machine learning and Azure fundamentals to students entering the field.

### Featured projects

| Project | What it shows |
|---|---|
| [**LLM Evaluation Harness**](https://github.com/Herizhaak/llm-eval-harness) | Three small open LLMs (360M–1.5B) on PubMedQA, CPU only: strict answer parsing, bootstrap CIs, McNemar/Holm paired tests and calibration. The best model beats "always yes" by 10 points, which is not significant at n = 120. An LLM judge was validated against known answers and control inputs, and it failed (κ = 0.18). |
| [**Hospital 30-Day Readmission**](https://github.com/Herizhaak/hospital-readmission-30day) | 99k real US hospital encounters, split by patient so no patient appears in both train and test. ROC-AUC 0.67 [0.66, 0.69]. Includes calibration, a threshold set by intervention capacity, and subgroup checks by age, race and payer. |
| [**Diabetes Risk API**](https://github.com/Herizhaak/diabetes-risk-api) | Model serving with FastAPI: validated inputs, a versioned model card, Prometheus metrics, prediction logging and a PSI/KS drift endpoint. 51 tests, Docker, CI. |
| [**Diabetes Risk: How Much Do the Blood Tests Do?**](https://github.com/Herizhaak/diabetes_pred) | Screening model with no blood test vs. one with HbA1c/glucose vs. the clinical rule. PR-AUC, out-of-fold thresholds, and a finding that the dataset's labels are partly rule-generated. |
| [**Heart Disease Risk Classifier**](https://github.com/Herizhaak/heart_disease_pred) | Four models compared with repeated CV, test ROC-AUC 0.90 (95% CI 0.80–0.98), interpretable odds ratios, tested prediction CLI. |
| [**Superstore Sales Analytics**](https://github.com/Herizhaak/superstore_forecast) | DuckDB SQL analysis, a Power BI dashboard, and a rolling-origin forecast backtest (Holt-Winters vs. seasonal naive vs. ARIMA). |

### Tools I use

- **Python and ML:** pandas, NumPy, scikit-learn, XGBoost, imbalanced-learn, statsmodels, Hugging Face Transformers
- **Evaluation:** cross-validation, PR-AUC / ROC-AUC, calibration, bootstrap confidence intervals, threshold selection, subgroup analysis, LLM-as-judge, inter-rater agreement (Cohen's κ)
- **Engineering:** FastAPI, Pydantic, pytest, GitHub Actions, Docker, Prometheus metrics, SQLite
- **Data and BI:** SQL (DuckDB), Power BI, Excel
- **Visualisation:** Matplotlib, Seaborn, Plotly
- **Cloud:** Microsoft Certified: Azure Fundamentals (AZ-900)

### Contact

[LinkedIn](https://www.linkedin.com/in/isaachiri) · [Kaggle](https://www.kaggle.com/isaachiri)

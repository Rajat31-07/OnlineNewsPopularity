

\# Article Popularity Prediction

Project repository for Data Science in Practice — Media Analytics



Predict online article popularity (e.g., shares or viral/not-viral) using machine learning and explainability techniques, and deploy a real-time prediction pipeline for editorial decision support.



---



\## Background of the Problem

Media companies and content creators struggle to predict which articles will gain traction online. Popularity is influenced by multiple factors—keywords, sentiment, timing, and social signals—making manual estimation unreliable.



---



\## Why is it Important?

Accurate popularity predictions enable media organizations to:

\- Optimize content strategies for higher engagement.

\- Improve ad revenue forecasting.

\- Reduce effort on low-impact articles.

\- Support data-driven editorial decision-making.



---



\## Objectives of the Project

1\. Build a model to predict article popularity (shares or viral/not viral).

2\. Explain key drivers of virality (feature importance \& model interpretability).

3\. Deploy a real-time prediction pipeline (API) for practical use.



---



\## How Can Data Science Solve the Problem?

\- \*\*Modeling:\*\* Linear Regression, LightGBM, XGBoost, CatBoost.

\- \*\*Explainability:\*\* SHAP/LIME to identify drivers of virality.

\- \*\*Operationalization:\*\* Batch scoring + real-time API for editorial tools.



---



\## Dataset

\*\*Source:\*\* UCI Machine Learning Repository — Online News Popularity



\*\*Summary:\*\* Extracted from Mashable articles over a period, including metadata, content features, and social engagement metrics.



\*\*Description:\*\*

\- \*\*Features:\*\* 58

\- \*\*Observations:\*\* ~39,000

\- \*\*Format:\*\* Tabular CSV



> Files expected under `data/`:

> - `data/online\_news\_popularity.csv` (raw)

> - `data/processed/train.csv`, `data/processed/test.csv` (created during preprocessing)



---



\##




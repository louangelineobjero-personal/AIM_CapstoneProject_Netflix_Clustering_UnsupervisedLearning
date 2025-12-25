# Netflix_Clustering_UnsupervisedLearning
Group users into distinct segments based on their viewing behavior and patterns. 


## Step 1: Problem Understanding & Framing
- Frame the business and data science problem clearly.
- Define the task type: classification, regression, recommendation, anomaly detection, or clustering.
- Specify success metrics: `Accuracy`, `AUC`, `RMSE`, `Silhouette Score`.
- Business KPIs: cost savings, uplift.
- **Capstone linkage:** Module 1 output maps to Capstone Steps 1–3.
- **Deliverable:** Clear problem statement + task type + target metric.

## Step 2: Data Collection & Understanding
- Use public datasets (Kaggle, UCI, APIs) or approved custom data.
- Summarize feature types, missing values, outliers.
- Provide a data dictionary (variables, types, units, allowed values).
- **Deliverable:** Dataset overview + data dictionary.

## Step 3: Data Preprocessing, Applied EDA & Feature Engineering
- Clean data: handle nulls, duplicates, outliers.
- Engineer features: scaling, encoding, binning, domain-derived features.
- Applied EDA: distributions, relationships, clustering tendency.
- Feature importance & explainability: `SHAP`, `LIME`, or model-based importance.
- Feature selection: filter, wrapper, or embedded approach.
- Dimensionality reduction: `PCA` (and `t-SNE`/`UMAP` for visualization if needed).
- **Deliverable:** EDA + Feature Engineering report with reproducible code & justifications.

## Step 4: Model Implementation
- Experiment with models:
  - Supervised: `Logistic Regression`, `Decision Trees`, `Random Forest`, `XGBoost`, `SVM`.
  - Unsupervised: `K-Means`, `DBSCAN`, Hierarchical (Elbow, Silhouette).
  - Recommendation: collaborative or content-based.
  - Deep Learning: `RNNs`, `CNNs`, `LSTMs`, `Transformers`.
- Evaluation: compare using relevant metrics.
- Reproducibility: save configs and artifacts (models/).
- **Deliverables:** Trained models, metrics, and comparison between models.

## Step 5: Critical Thinking → Ethical AI & Bias Auditing
- Explain model decisions (`SHAP`, `LIME`, `PDP`, `ICE`).
- Address limitations: imbalance, leakage, overfitting.
- Bias detection & fairness audits:
  - Check outputs across sensitive groups (gender, race, age, socioeconomic status).
  - Use fairness metrics: `demographic parity`, `equalized odds`, `disparate impact`.
  - Propose mitigations: reweighting, thresholds, augmentation, post-processing.
- **Deliverable:** Bias & Fairness Analysis section in the final report.

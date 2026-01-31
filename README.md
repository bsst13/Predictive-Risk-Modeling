🛡️ Multi-Stage Predictive Risk Modeling
Portfolio Project: Strategic Churn & Retention Analytics
📌 Executive Summary
This project develops a high-precision predictive engine to identify "At-Risk" profiles within a multi-stage lifecycle. By comparing XGBoost and Neural Network architectures, I demonstrate how incorporating incremental data stages (Engagement & Performance) significantly reduces false negatives, allowing for proactive intervention strategies.

🛠️ Technical Deep-Dive
1. Data Engineering & Pipeline
Multi-Stage Framework: Built three distinct models to evaluate predictive uplift as more features became available.

Feature Engineering: Managed high-cardinality categorical variables and performed rigorous scaling for Neural Network stability.

2. Model Architecture & Comparison
XGBoost: Utilized for its superior handling of tabular data and built-in feature importance.

Neural Networks: Optimized with manual hyperparameter tuning (Learning Rate, Dropout, Activation Functions) to benchmark against tree-based methods.

Interpretability: Integrated SHAP (SHapley Additive exPlanations) to provide "Glass-Box" transparency into "Black-Box" models.

3. Key Results
AUC Improvement: Achieved a peak AUC of 0.9745 in Stage 3.

Precision/Recall: Balanced the model to minimize False Negatives (critical for identifying all at-risk units).

Tuning Impact: Proved that while XGBoost is strong out-of-the-box, Neural Networks show the highest gain from hyperparameter optimization on complex datasets.

🧪 Tech Stack
Languages: Python (Pandas, NumPy)

ML Frameworks: Scikit-Learn, XGBoost, TensorFlow/Keras

Explainable AI: SHAP

Visualization: Matplotlib, Seaborn

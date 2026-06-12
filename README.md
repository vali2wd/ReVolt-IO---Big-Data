# E2E Big Data & Machine Learning Pipeline: Time Prediction for ReVolt IO sessions

A complete end-to-end data pipeline demonstrating scalable Data Engineering and predictive modeling on a ReVolt IO post-2023 organized sessions (~1.5m races). This project covers the entire data lifecycle: from distributed ingestion and processing to advanced hyperparameter tuning and Deep Learning architectural design.

### 🛠️ Tech Stack
* **Data Engineering & ETL:** Apache Spark (PySpark), Spark SQL, Python (Pandas)
* **Machine Learning:** PySpark MLlib (Linear Regression, K-Means Clustering, Cross-Validation)
* **Deep Learning:** TensorFlow / Keras (Sequential MLP, Activation Functions, Dropout Regularization)

### 🚀 Key Highlights
* **Distributed Processing:** Engineered scalable data transformation pipelines utilizing PySpark and custom UDFs for efficient memory and cluster management.
* **Feature Engineering:** Managed high-cardinality categorical variables through systematic grouping, One-Hot Encoding, and feature scaling (`StandardScaler`).
* **Model Optimization:** Implemented rigorous hyperparameter tuning using Grid Search and Cross-Validation (ElasticNet/Lasso/Ridge regression) to prevent overfitting and ensure mathematical robustness.
* **Comparative Analytics:** Architected and evaluated a Deep Learning neural network against a baseline PySpark regression model, analyzing performance trade-offs (RMSE) and compute efficiency.
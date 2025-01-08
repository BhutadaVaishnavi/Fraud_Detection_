**Fraud Detection System**
Objective: Developed a machine learning-based system to detect fraudulent financial transactions using anomaly detection techniques.

Data Preprocessing:
Cleaned and prepared data by handling missing values and ensuring consistency across columns.
Encoded categorical features such as type into numerical representations for model compatibility.
Scaled numerical features like amount, oldbalanceOrg, and newbalanceOrig to optimize model performance.

Exploratory Data Analysis (EDA):
Analyzed transaction patterns to uncover relationships between features and fraudulent activities.
Visualized key insights using histograms, box plots, and heatmaps to detect anomalies and trends in fraudulent vs. non-fraudulent transactions.
Identified significant variables influencing fraudulent activities, such as transaction type and balance changes.

Feature Engineering:
Derived additional insights by calculating balance differences and transaction proportions.
Assessed correlations among features to minimize redundancy and improve model interpretability.

Model Development:
Implemented anomaly detection algorithms, including Isolation Forest, Local Outlier Factor, and One-Class SVM.
Tuned hyperparameters such as contamination, n_estimators, and gamma to improve detection accuracy.
Used a random state for reproducibility and generated synthetic outliers for model validation.

Model Evaluation:
Evaluated models using metrics such as accuracy, precision, recall, and F1-score.
Achieved a robust fraud detection system with high precision in identifying anomalies.
Provided classification reports highlighting the performance of each model.

OVERVIEW:
Identified patterns in fraudulent transactions, such as larger transaction amounts and specific transaction types (e.g., CASH-OUT, TRANSFER).
Recommended data-driven strategies for financial institutions to mitigate fraudulent activities.

Technologies Used:
Programming Tools: Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
Machine Learning Algorithms: Isolation Forest, Local Outlier Factor, One-Class SVM

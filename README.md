# MLOps_assignment2
This MLOps pipeline was designed and implemented for the Fashion MNIST dataset to ensure continuous improvement, explainability, and efficient model management. 

Team Members:
1. Pramit Saha - 2023aa05416
2. Soumili Saha - 2023aa05980
3. Shivang Sharma - 2023aa05277
4. Md Mehran Abul - 2023aa05363


One-Page Summary for MLOps Assignment

1)	Description of the Work Completed
This MLOps pipeline was designed and implemented for the Fashion MNIST dataset to ensure continuous improvement, explainability, and efficient model management. The workflow includes the following steps:
1. Exploratory Data Analysis (EDA)
•	Automated EDA was performed using Sweetviz, generating visual reports on class distribution, feature relationships, and missing values.
•	Additional Seaborn & Matplotlib plots were used to analyze data patterns.
2. Feature Engineering & Explainability
•	Data preprocessing was implemented using Scikit-learn, including normalization and scaling for better model performance.
•	Feature importance was analyzed using SHAP, ensuring that selected features contributed meaningfully to predictions.
3. Model Selection & Hyperparameter Optimization
•	TPOT (AutoML) was used to explore different model architectures and identify the best-performing one.
•	Optuna was applied for hyperparameter tuning, optimizing parameters such as learning rate, regularization, and model complexity.
4. Model Monitoring & Performance Tracking
•	MLflow was integrated to track model performance, log experiments, and ensure reproducibility.
•	Drift detection mechanisms were set up to monitor model degradation and signal the need for retraining.
5. Version Control & Reproducibility
•	Git & Git LFS were used for source code and large file management.
•	DVC (Data Version Control) was implemented to track dataset changes, ensuring consistency across experiments.
6. Deliverables & Documentation
•	The processed data, trained models, and source code were packaged into a zip file for easy reproducibility.
•	A one-page summary was created explaining key choices and best practices.
•	A screen recording (5 minutes) was made to present the implementation and results.
This pipeline ensures automation, reproducibility, and model explainability, following MLOps best practices for continuous model improvement.
2)	Justification for the choice of libraries/tools.
Each library was chosen based on its suitability for automating and streamlining different MLOps tasks:
•	EDA & Visualization:
o	Sweetviz: Generates automated exploratory reports with visual insights.
o	Matplotlib/Seaborn: Provides detailed visualizations of dataset distributions.
•	Feature Engineering & Explainability:
o	Scikit-learn: Standard preprocessing utilities like scaling and normalization.
o	SHAP: Model explainability to identify feature importance.
•	Model Selection & Hyperparameter Tuning:
o	TPOT: Automates model selection using genetic algorithms.
o	Optuna: Efficient hyperparameter tuning via Bayesian optimization.
•	Model Monitoring & Tracking:
o	MLflow: Logs experiments, tracks models, and provides version control.
o	DVC (Data Version Control): Manages large datasets and tracks file changes efficiently.
These tools were selected to ensure automation, scalability, and reproducibility, which align with best MLOps practices.
3)	Explanation of how each functionality contributes to MLOps best practices.
EDA Reports	Automates data insights, enabling informed preprocessing decisions.
Feature Engineering	Ensures consistent data preprocessing, making models more robust.
Explainability	Improves model trust and fairness by interpreting predictions.
AutoML & Hyperparameter Optimization	Standardizes model selection and prevents overfitting.
Model Tracking (MLflow)	Enables reproducibility and performance comparison over time.
Drift Detection	Identifies when retraining is needed to maintain accuracy.
DVC	Ensures version control for large datasets.
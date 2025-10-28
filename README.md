# Mood-Disorder-Prediction
This project leverages Databricks and AWS (RDS/S3) to develop a privacy-first, scalable machine learning pipeline for predicting mood disorders from clinical health records. Over 40,000 behavioral and diagnostic records were ingested and processed via automated ETL workflows, ensuring compliance with privacy and ethical standards.

A comprehensive feature engineering process distilled 60+ predictors from text, categorical, and numerical data. Advanced ensemble models (Random Forest, Extra Trees) were trained and validated using cross-validation, achieving 92% accuracy and perfect recall for minority at-risk classes. Model interpretability was prioritized through SHAP and permutation importance analyses, allowing clinicians to understand and act on the primary drivers of risk, such as sleep, exhaustion, and euphoria.

Visualizations, confusion matrices, and ROC curves are included for thorough model evaluation. The project is fully modular, with cloud-based configuration files and reproducible Databricks notebooks, enabling easy scaling, collaboration, and deployment in real-world clinical settings.

Tech Stack: Python(Pandas, Numpy, scikit-learn, Random Forest, Extra Trees, cross validation, SHAP), Databricks, AWS RDS, AWS S3, Jupyter Notebook

Link to Google Colab Notebook: https://colab.research.google.com/drive/14dIrMxjuBprbVqeoWUFgm2OfL2fFLDkz?usp=sharing

# **Applied-AI-ML-Capstone-Project**

## Housing Value Prediction Project

### Project Description
* This project is part of the Applied-AI-ML-Capstone-Project, where the goal is to build an end-to-end data intelligence system. It covers four stages.

### Data ingestion & exploratory analysis
* Supervised machine learning
* Ensemble modeling & pipelines
* LLM-powered feature
* We focus on cleaning the dataset, handling missing values, correcting data types, detecting outliers, and performing exploratory data analysis with visualizations and correlation studies. The cleaned dataset is saved for use in later parts.

### Dataset
* We used the California Housing dataset, a well-known structured dataset available via scikit-learn.
* Reason for choice:
  * Contains >20,000 rows (well above the minimum requirement of 500).</li>
  * Includes multiple numeric columns (e.g., MedInc, HouseAge, AveRooms, AveBedrms, Population, AveOccup, Latitude, Longitude).
  * Includes categorical columns when extended with derived features (e.g., region bins).
  * Target variable MedHouseVal is continuous, suitable for regression, and can be binarized for classification tasks.
  * Publicly available and widely used for benchmarking ML models.
    
### Technologies Used
* Python 3.9+
* Pandas for data manipulation
* NumPy for numerical operations
* Matplotlib & Seaborn for visualizations
* Scikit-learn for correlation, preprocessing, and ML models

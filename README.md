# Wine-Quality-Analysis
This repository details a data-driven analysis of red wine characteristics to understand and predict wine quality.

# Project Overview:

Objective: Explore the chemical properties of red wine and their correlation with quality, and develop machine learning models to predict wine quality.

Data Preparation: Features were scaled using StandardScaler, and data was split into 80% training and 20% testing sets.

Model Comparison:
Decision Tree Classifier: Achieved an accuracy of 58.44% but struggled with predicting minority quality classes (e.g., very high or very low quality wines).
Random Forest Classifier: Performed slightly better with an accuracy of 59.69%, showing better generalization, though it still faced challenges with minority classes.

Key Feature Importance (from Random Forest Model):
Alcohol (highest importance)
Sulphates
Total Sulfur Dioxide
Volatile Acidity

Key Chemical Property Insights:
Strong Positive Correlation with Quality: Alcohol, Sulphates, Citric Acid. Higher levels generally indicate better quality.
Strong Negative Correlation with Quality: Volatile Acidity, Total Sulfur Dioxide, Density. Higher levels generally indicate lower quality.
Volatile Acidity: A critical factor, as wines with higher volatile acidity tend to be rated lower in quality.

Files:
wine_data.csv: Dataset containing chemical properties and quality ratings of red wines.
wine.ipynb: Jupyter Notebook with the data exploration, analysis, and machine learning model implementation.
Wine_Quality_Analysis_Presentation.pptx: Presentation summarizing the wine quality analysis and model results.
Pictures of all outputs obtained.

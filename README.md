# Exploratory-Data-Analysis-EDA-
 Objective: Understand data using statistics and visualizations. Tools: Pandas, Matplotlib, Seaborn, Plotly
The analysis is structured around the Titanic-Dataset.csv file. Tools Used:
Python
Pandas: For data loading and manipulation.
Matplotlib & Seaborn: For data visualization.
Analysis :
This EDA follows a structured approach to investigate the dataset:
Summary Statistics: Generated descriptive statistics (mean, median, standard deviation, etc.) for numerical features like Age and Fare.
Numeric Feature Visualization: Created histograms and boxplots to understand the distributions and identify outliers in Age and Fare.
Feature Relationships: Used a correlation matrix (heatmap) and a pairplot to visualize the relationships between different features (e.g., Pclass, Fare, Survived).
Pattern Identification: Identified key patterns, trends, and data anomalies.
Inference: Drew basic inferences from the visuals to form initial hypotheses.
Key Findings & Insights
Survival Rate: A majority of passengers (approx. 61.6%) did not survive the disaster, while 38.4% did.
Gender Impact: Sex is one of the strongest predictors of survival. Female passengers had a significantly higher survival rate than male passengers.
Class Impact: Pclass (Passenger Class) is strongly correlated with survival. 1st class passengers had a much higher chance of surviving than 3rd class passengers.  
Fare: Fare is positively correlated with survival—passengers who paid more (likely for 1st class tickets) had a better survival rate
Data Anomalies: The lataset has significant missing values that would need to be handled before machine learning:
Cabin: ~77% of values are missing
Age: ~20% of values are missing
# Competition
Kaggle, SIGNATE, ProbSpace, etc.

## important things of data analysis
CRISP-DM (Cross industry standard process for data mining)<br>
https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining

### 1, Business Understanding
```
What is the purpose of this?
What's important.
The importance of hypothetical thinking.
```

### 2, Data Understanding
```
Check each feature name and its meaning in the data
Check the size of the data (.shape in pandas)
Display a portion of the table (pandas's .head())
Type check (pandas's .dtypes())
Check statistics such as average, maximum, and minimum values for each feature (pandas's .describe())
Checking missing values (pandas.isnull().sum())
Visualization of distribution by histogram
Visualize the relationship between the target variable and the explanatory variable using scatter plots and box plots.
For time series data, visualize the time series trend.
Check outliers.
Visualization by dimensionality reduction

Useful tools
pandas-profiling
missingno
seaborn.heatmap
```

### 3, Data Preparation
```
Remove outliers
Completion or removal of missing values
Logarithmization of numeric features
Categorization of Numerical Features
Normalization of Numerical Features
Dummy Variableization of Categorical Features
Aggregation of Categorical Features
Combinatorial Feature Generation for Categorical Features
Polynomial Feature Creation


Useful Tools
sklearn.preprocessiong
featuretools (a tool that automatically generates features for you)
automl libraries (tools for optimization, including preprocessing and modeling)
auto-sklearn
TPOT
```

### 4, Modeling
```
Correlation coefficients between objective and explanatory variables
Extraction by Lasso or Ridge regression
Importance extraction using decision tree-based models (Random Forest, XGBoost, LightGBM)


Learning model interpretation methods (LIME, SHAP)
Visualization of decision trees (dtreeviz)
　By determining the importance of features, we can consider what features are important and what features are unnecessary. The results can be used to recreate the features or to assist in model interpretation.


sklearn.feature_selection.SelectKBest
sklean.feature_selection.RFE
sklearn.feature_selection.SelectFromModel
mlflow (a tool to manage your models)

```
### 5, Evaluation
```
Evaluate the accuracy of the model
Determine if improvements should be made
```
### 6, Deployment
```
Take action based on the results obtained.
```

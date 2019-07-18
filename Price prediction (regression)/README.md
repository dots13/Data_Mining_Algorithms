House price dataset.
The first part is data preprocessing:
- Attribute selection based on the correlation matrix.
- Clearing data, finding outliers, filling in missing values.
- Scaling data.

Used models:
- DecisionTreeRegressor
- RandomForestRegressor
- XGBRegressor

For searching best params - GridSearchCV
For validation - RMSLE
Reduce dimension PCA 

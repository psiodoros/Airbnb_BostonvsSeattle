# Airbnb_BostonvsSeattle
Analyzing and comparing airbnb listing data between Boston and Seattle
# Motivation
The project was made as part of the Udacity Data Science Nanodegree program.
I used the price and the price/accommodation as the main features to try to get a clear view in the following questions:
1. Which city has the highest rates?
2. Is the difference in rates same among different roomtypes?
3. What are the strongest predictors for price?
# Files
1. csv data files, they contain the listings data, one for each cities
2. png files that contain the graphs that came from the analysis made in the jupyter notebook
3. the Jupyter Notebook with all the data preparation and analysis
# Libraries used
1. pandas ,numpy, seaborn ,warnings , matplotlib.pyplot 
for data analysis
3. sklearn.preprocessing.MultiLabelBinarizer 
for converting many-valued column into corresponding binary features
4. sklearn.linear_model.LinearRegression , sklearn.ensemble.RandomForestRegressor 
, sklearn.model_selection.train_test_split , sklearn.metrics.r2_score and mean_squared_error
for the ML analysis
# Results
The analysis shown that Boston rates are significant higher than Seattle , 
though this difference reduces in bigger properties. 
With the city, neighborhood, host history, review ratings to be among the strongest factors that define price.
A blog post describing the results of this analysis can be found in
https://medium.com/@psiodoros/boston-vs-seattle-airbnb-rates-4a8a5b3953db
# Acknowledgements
Credit to the AirBnB datasets hosted by Kaggle, the datasets are here 
Seattle: https://www.kaggle.com/airbnb/seattle
Boston: https://www.kaggle.com/airbnb/boston

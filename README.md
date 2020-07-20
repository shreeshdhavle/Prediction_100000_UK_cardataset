# Prediction_100000_UK_cardataset
Kaggle dataset: https://www.kaggle.com/adityadesai13/used-car-dataset-ford-and-mercedes

The details about the dataset is available on the url provided above.
The main task was to apply prediction model.
Types of Regression model considered where Linear, Support vector regression,
Lasso, Ridge, Decision tree regression, Random forest regression, Gradient Boosting regression,
AdaBoost Regression, XG boost regression.

Approach considered:
The dataset was cleaned with no null values. Hence lot of work was saved.
The year column was converted into the age of car. The categorical variables where converted into numerical form. 
Then all the above regression model was applied to get the r-squared score on the test data for comparison.
We found out that Random Forest Regression and eXtreme Gradient Boost regression had r-squared score of 95.6% and 95.3% respectively on the test data. 
Hence the further hyper parametric tuning was done on the both the above model and was found out to be 96.18%.

Future Working:
More efforts can be given on tuning the parameters which will increase the accuracy. 

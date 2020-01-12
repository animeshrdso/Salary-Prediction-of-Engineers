# Salary-Prediction-of-Engineers
The government of India needs to
prioritize higher education and undertake long
term policy interventions in the next 5 10 years to ameliorate the low rate of
engineering employability. We tried to predict
the salary of an Engineer based on some parameters defining their past
performance.

* The training set consisted of salary of 3000 engineering students depending upon 35 different features.
* The training data contained missing data in different columns(or features) where we used different methods to handle them.
* Feature engineering was used where we tried to combine and remove various columns.
* For the prediction of the salaries R-Squared Error was used as the evaluation 'metric'.
* Finally RandomForestRegressor and XGBoost was tried to fit on our model.
* The final scores from two different models was found to be low on test data because the training data was less and had a lot of missing values.

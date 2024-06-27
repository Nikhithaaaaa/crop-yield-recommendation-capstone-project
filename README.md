# crop-yield-recommendation-capstone-project
capstone project on crop yield recommendation and model building
abstract :
India being an agriculture country, its economy predominantly depends on agriculture yield growth and agro-industry products.
Data Mining is an emerging research field in crop yield analysis. Yield prediction is a very important issue in agricultural.
objective:
Crop yield prediction is an important aspect of agriculture that helps farmers make informed decisions about their crops. 
Develop machine learning models that can accurately detect crop diseases and estimate crop yield to enable highest crop yield.
Executive summary:
By improving the crop variety through cross-breeding and hybridization, the crop yield can be increased. 
The crop becomes resistant to biotic and abiotic stresses. For short-duration crops, the early maturing varieties can fit the crop into multiple cropping varieties.
Problem statement :
Crop yield prediction dataset is a “REGRESSION” problem statement.
Crop yield prediction is an essential task for the decision-makers at national and regional levels for rapid decision making. 
An accurate crop yield prediction model can help farmers to decide on what to grow and when to grow.
SIGNIFICANCE:
The stakeholder is facing a problem in predicting the yield for crop. stakeholder needs help in suggesting crop yield.
Data is collected from “kaggle” datasets website as it has various features related to yield prediction which helps in cultivating specified crop related to the season.
This machine learning models will give predicted crop yield and recommended to farmers based on their soil the crop is grown. 
 checking null values:
Checked null values in the dataset and dropped the duplicate values from dataset.
CHANGING OF DATA TYPES:
A column called “average_rain_fall_mm_per_year” has been transformed it’s data type from string(object) to float.

DROPPING OF UNNAMED COLUMNS : 
Dropping unnamed columns that does not have effect on dependent columns .
Categorical variable analysis:
Observing distribution of different categorical variables.
Creating bar charts or pie charts to visualize the proportions of different categories.


DATA SPLITTING :
Splitting of data into train data and test data by Re-arranging columns .
This data splitting occurs as X and Y by giving them respective column names. 
ILOC () : an index-based method used for data selection.
MODEL SELECTION :
Crop yield prediction is a regression problem statement .regression models for predicting crop yield prediction dataset 
LINEAR REGRESSION: LR analysis is used to predict the value of a variable based on value of another variable.

LASSO: it is a regression analysis method that performs both variable selection and regularization that enhance prediction accuracy.
RIDGE :in ridge regression , the coefficients are towards zero but never exactly equal to zero.


DECISION TREE REGRESSOR : it is a supervised machine learning algorithm that is used by train using “autoML” tool and regresses the data using true or false conditions.

RANDOM FOREST REGRESSOR :supervised learning algorithm and bagging technique that uses an ensemble learning method for regression in machine learning.

GRADIENT BOOSTING REGRESSOR:GBR trees are based on idea of ensemble method derive from a decision tree.
EVALUATION METRICS :
Root mean SQUARED error : coefficient of determination .
RMSE measures the average difference between values predicted by a model and the actual values. It also provides an estimation of model that is able to predict the target value accuracy.
MEAN absolute ERROR : MAE  is a measure of errors between paired observations expressing the same phenomenon.

RESULTS AND CONCLUSION:
Among all ML models gradientboostingregressor (gbr) given the best results. i.e.., accuracy or test score is 96.90%

MAE : 8723.21801792049.

RMSE : 14925.011052145841 .
Business insights :
Crop yield prediction dataset project majorly gives the farmers and also the stakeholders correct accuracy of predicting the crop yield and helps in suggesting the crop for various seasons based on crop growth .

 and also this helps in identifying the best methods for crop growth regularly which leads to higher crop yield.

This helps in increasing the market value for respective crops and analysis of crop yield makes very easy.



# Avocado Average Regression


Firstly we did some feature engineering like remove useless feature and split date feature.We
did plot of Avocado’s Average Price through the Date column to see average price on dates. When we looked heat map ,we saw features are not correlated with each other.So we decided
to look two features:region and type.We thought region is so complex and we dropped the
column. We split data for regression models.We compared each model with the Rmse values
and we looked plot for predictions.We compared every model’s Rmse in the table in
code. Our first model is Support vector regression. Support vector’s Rmse is :“0.32709960802239246”. We continued with Linear regression for compare them. Linear regression’s Rmse is :”0.3018079323902026”. The Rmse is low so we can say that we have a good model but below in the
scatter plot doesn't have straight line.Linear regression's Rmse is lower than Support
vector regression's Rmse.That’s why Linear regression algorithm model better than
Support vector regression algorithm. We continued with Decision tree regression for compare them. Decision tree regression’s Rmse is :”0.21163020215875009” The RMSE is lower than Lineer Regression RMSE and nearly have a straigt line. The Decision tree regressor better than the Linear regression model. We continued with Random forest regressor for compare them. Random forest regression’s Rmse is :”0.14625075734729556” The RMSE is lower than the three previous models, so the Random forest regressor is
the best model in this case.We looked distributed plot that our residuals looked to be
normally distributed which means that our model was a correct choice for the data. Finally We have straight line in best model. According to comprasion of model's RMSE ,we can see which model is the best
choice for our dataset. Random forest regression has minimum RMSE value in the
table.In this case our best model is Random Forest Regression

# Housing Price Prediction
![Header](https://github.com/xavier-lim/housingPricePrediction/blob/master/images/housesbanner.png)

This project consists of using home features to predict the final price of homes in Ames, Iowa. I created numerous XGBoost regression models with varying parameters to determine the best model to make these predictions. This type of analysis would be valuable for home buyers when determining the value of a house.


## Table of Contents
1.	[Project Tools](https://github.com/xavier-lim/housingPricePrediction#project-tools)
2.	[Data Source](https://github.com/xavier-lim/housingPricePrediction#data-source)
4.	[Exploratory Data Analysis](https://github.com/xavier-lim/housingPricePrediction#exploratory-data-analysis)
5.	[Conclusion](https://github.com/xavier-lim/housingPricePrediction#conclusion)
7.	[Author](https://github.com/xavier-lim/housingPricePrediction#author)

## Project Tools
*	Python
*	Jupyter Notebook
*	Train csv file
*	Test csv file

## Data Source
All the data for this project was collected from [Kaggle](https://www.kaggle.com/c/home-data-for-ml-course/overview):

1.	The **Train** data set presents 79 features about 1460 houses in Ames and the price of each house.
2.	The **Test** data set presents 79 features about 1459 houses in Ames without a price.



## Exploratory Data Analysis
![Correlations](https://github.com/xavier-lim/housingPricePrediction/blob/master/images/correlations.PNG)

Many numerical variables such as OverallQual, GrLivArea, TotalBsmtSF, 1stFlrSF, YearBuilt, FullBath, and GarageArea appear to have a strong positive correlation with the sale price of a home.

## Conclusion
After submitting my model to the Kaggle competition, I finished in the Top 7% with an MAE of under 15,000. In conclusion, the XGBRegressor and the predictor variables I selected effectively predicted house prices of homes in Ames, Iowa


## Author

* **Xavier Lim** - [LinkedIn](https://www.linkedin.com/in/xavier-lim14/) | [Portfolio Website]( https://xavier-lim.github.io/)

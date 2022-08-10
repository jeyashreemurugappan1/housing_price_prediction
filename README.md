# housing_price_prediction
This project aims at predicting factors on which sale price is depending up based

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- What is the background of your project?
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.  
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
The company wants to know:
    Which variables are significant in predicting the price of a house, and
    How well those variables describe the price of a house.
- What is the business probem that your project is trying to solve?
This project is trying to predict the factors on which Sale price depends 
- What is the dataset that is being used?
https://github.com/jeyashreemurugappan1/housing_price_prediction/data/train.csv

## Conclusions
<span style="color:brown">Sale Price is more on below predictive factors.</span>
<br>
<span style="color:blue"> When feature `GrLivingArea` is more (Sale price is more when ground floor living area is more) </span>
<br>
<span style="color:blue"> With feature `OverallQual` rating is more sale price is more </span>
<br>
<span style="color:blue"> When feature `TotalBsmtSF` is more  sale price is more</span>
<br>
<span style="color:blue"> When featue `LotArea` is more sale price is more</span>
<br>
<span style="color:blue"> When `MsZoning` is Residential Low Density sale price is more</span>
<br>
<span style="color:blue"> When `MsZoning` is Floating Village Residential sale price is more</span>
<br>
<span style="color:blue"> When `OverallCond` rating of condition of house is more sale price is more</span>
<br>

<span style="color:brown">Sale Price is low on below predictive factors.</span>
<br>
<span style="color:blue"> When `age` of house is high (year of construction of house to till date) lower is sale price due to depreciation </span>
<br>
<span style="color:blue"> When `MSSubClass` -type of dwelling involved in sale 90-DUPLEX - ALL STYLES AND AGES sale price is low</span>
<br>
<span style="color:blue"> When `Neighborhood` - Physical locations within Ames city limits is -MeadowV	Meadow Village , sale price is low</span>
<br>
<span style="color:blue"> When `Exterior2nd` - Exterior covering on house (more than one material) is Wd Sdng Wood Siding, sale price is low</span>

## Technologies Used
- Pandas - 1.3.4 
- Numpy - 1.20.3 
- Seaborn - 0.11.2
- Matplotlib - 3.4.3
- scikit-learn - 0.24.2
- statsmodels - 0.12.2


## Acknowledgements
Give credit here.
- This project has been prepared from learning from Advanced Linear regression at https://www.learn.upgrad.com


## Contact
Created by [@jeyashreemurugappan1] - feel free to contact me!
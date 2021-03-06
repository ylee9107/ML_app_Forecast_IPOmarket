# App to Forecast IPO market

## Introduction:

A IPO is called an Initial Public Offering, it is where companies will offer the public to buy in on shares of the company. Buying into an IPO can be a great opportunity for investment depending on the market and its influences. This project aims to use machine learning techniques to aid in the decision of which IPOs are worth a closer look and which ones are not. 

## The breakdown of this project:

- Learning about the IPO market
- Data cleaning and feature engineering
- Logistic Regression to perform Binary classification
- Model Evaluation
- Feature importance

## Let’s begin with What is an IPO?

Well, it is when a private company turns into a public company. It is a way to raise capital and provides an opportunity to invest in the company. Companies can do this by enlisting the aid of one or more investment institutions/banks to underwrite the company's offering. To clarify, this means that the banks will make a guarantee to purchase all the shares offered at the IPO price on the day and head out for a roadshow. The purpose of the roadshow is to gain interest from institutional clients where they would subscribe for the shares, this means that they indicate interest in buying the shares on the day of opening. The underwriter then set the offer or IPO price which is dependent on the level of interest.

Another interesting feature is that there seem to be a systematic underpricing of IPOs where billions of dollars are left on the table. Money left on the table can be described as the difference between the offer price and the first day's closing price. Additionally, to get a better deal than the opening price requires a broker on your behalf, otherwise you'll pay the higher (opening) price. 

The model here would be built under these assumptions.

## Data:

The data is recent and sourced from https://www.iposcoop.com/scoop-track-record-from-2000-to-present/. It is downloaded and saved into a folder. Note that it is not possible to read the data with 'Pandas' package, so the 'xlrd' package is used instead.

## Summary:

From this project, I’ve learnt and developed a better understanding of the modelling process, beginning from data cleaning, feature engineering and to testing. I was able to split the data into training and testing sets, utilising the Logistic Regression model to fit the training set and subsequently test it on the testing data set. I was able to discover which features influences the model, by simply looking at the coefficients of the logistic regression function as well as using the Random Forest Classifier to find the true impact of a given feature. Further, I was able to discover some limitations about extracting useful features, such as historical data or the frequency of certain types of data/data points that may not be useful in modelling.



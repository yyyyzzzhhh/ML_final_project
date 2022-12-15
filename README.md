# ML_final_project
## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
In this project, our problem is to use machine learning method to predict housing prices with a specific dataset. The general goal for this project is to model the housing price well, so people who use our model can acquire a guidance on the expected price based on the information of the property.

We applied knowledge learnt from lectures and homeworks to the models and evaluation methods we used. For models, we used SVM, Random Forest and three kinds of Boosting methods as a baseline, and then applied clustering on them for a comparison. Also, we use RMSE as a numerical evaluation standard and gridSearch and Cross Validation to train the model. We also used some methods taught in class to divide our dataset into training and testing sets. More details will be demonstrated in parts below.

One of the real-world implications of this problem is that it can provide valuable insights into the housing market. For example, the predictions made by the model can be used by real estate agents and property investors to make smarter decisions about buying and selling time. Additionally, the model can be used by policy makers to identify trends and patterns in the housing market, which can help to inform the development of housing policies.

This project also has its uniqueness. It allows for the identification of patterns and trends in historical housing data. This can then be used to make more accurate predictions about future housing prices. Additionally, machine learning models can be trained to clarify various different factors that may affect housing prices, such as the location, size, and features of a property. This can help to provide a more comprehensive and accurate prediction of housing prices.

Probably, there have been many people using ML methods to predict housing prices, but each prediction is unique due to its own model selections and uniqueness of datasets. We use a dataset from an ongoing Kaggle challenge, the inputs are variables of the house, like the building class, size, general shape of the property, type of roof, and many features that customers will pay attention to when they shop for housing.

There could potentially be some ethical implications of this problem, too. For example, if the predictions made by the model are used to make decisions about who can afford to buy certain properties or to set the prices of properties, this could potentially lead to discrimination against certain groups of people. Additionally, if the model is not trained on a diverse enough dataset, it could perpetuate existing biases and lead to unfair and inaccurate predictions. It is important to carefully consider the potential ethical implications.
    
## Technologies
Project is created with:
* Lorem version: 12.3
* Ipsum version: 2.33
* Ament library version: 999
    
## Setup
To run this project, install it locally using npm:

```
$ cd ../lorem
$ npm install
$ npm start
```

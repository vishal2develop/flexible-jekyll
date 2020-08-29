---
layout: post
title: "Bigmart Sales Prediction"
date: 2020-08-26 13:32:20 +0300
description: Using Data Science & Machine Learning to predict the sales at Bigmart. # Add post description (optional)



img: bigmart.png # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Data-Science, Machine Learning]
---
> This post is a brief summary of my approach on Analytics Vidhya’s Bigmart Sales Prediction problem using Python. You can find the complete article on [Medium](https://medium.com/p/bigmart-dataset-sales-prediction-c1f1cdca9af1?source=email-44ce830f39d8--writer.postDistributed&sk=4d7ce1822c12b7ca5a82acda8b5aecbe). 

## The Problem Description
> The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and find out the sales of each product at a particular store.

> Using this model, BigMart will try to understand the properties of products and stores which play a key role in increasing sales.

![Sales Prediction]({{site.baseurl}}/assets/img/sales.png)

### Find the entire notebook on GitHub: [BIGMART SALES PREDICTION](https://github.com/vishal2develop/Machine-Learning/tree/master/Bigmart-Sales-Prediction) 

**Metric Used —** ***Root Mean Squared Error***

---

> Essential Workflow of a Machine Learning Project.

+ Understand your data, and what results you are trying to get.
+ Do some visualization to know the distribution
+ Treat outliers and missing values
+ Find correlations between the features and the target variable
+ Next is feature selection
+ Normalization if required
+ Split the dataset for training and test data
+ Tune the model
+ Verify your results on the test set and model evaluation

---



>This was a great project to get my hands dirty on. The data was messy required a lot of:
1. Data Cleaning
2. Feature Engineering
3. Patience

**Some Handy Data Visualizations**
---

![Sales Prediction]({{site.baseurl}}/assets/img/collage.png)



### Models Built:

| Models                    | R<sup>2</sup>          | RMSE           | MAE              |
| ------------------------- |:----------------------:| --------------:| ----------------:|
| Linear Regresiion         | 0.501                  | 1205.05        |     NA           |
| Decision Tree Regressor   | NA                     | 1161.40        |     625.88       |
| Random Forest Regressor   | 0.675                  | 946.34         |     NA           |  


### Summary


This was a great learning project for me as I applied a lot of different techniques and researched a lot on different issues I faced throughout the duration of the project. I would like to thanks  [Analytics Vidhya](https://www.analyticsvidhya.com/) team for hosting this challenge. Also, kudos to [Towards Data Science](https://towardsdatascience.com/?gi=7dfaef49f9a) for their amazing content on different aspects of Data Science.

**Follow me on [Medium](https://medium.com/p/bigmart-dataset-sales-prediction-c1f1cdca9af1?source=email-44ce830f39d8--writer.postDistributed&sk=4d7ce1822c12b7ca5a82acda8b5aecbe)** 

# Walmart-Store-Sale-Prediction
Predicted store wide sales using historical sales data of 45 Walmart stores in different regions included the effect of Markdown events on sales to avoid overstocking or under stocking 
Project Abstract

Problem Statement

Predicting sales for a store is very important to estimate the quantity for each product / item. It saves them from the problem of overstocking or understocking. Machine learning algorithms have a pretty good performance on this purpose.

Our dataset is based upon sales information provided by Walmart. We are provided with historical sales data for 45 Walmart stores located in different regions. Each store contains a number of departments. Our aim is to solve this problem by predicting the department-wide sales for each store. In addition, Walmart runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of which are the Super Bowl, Labor Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks. Part of the challenge is modeling the effects of markdowns on these holiday weeks in the absence of complete/ideal historical data.

Proposed techniques and data science methodology

We intend to perform several algorithms such as Random Forest, nearest neighbour and SVM to predict the sales data. If possible, we might implement neural networks as well. We would also like to compare the accuracy of these models to determine which would be the most suitable for this kind of prediction.

Dataset

The data set contains four files, namely: stores. train, test and features.
1.	stores - This file contains anonymized information about the 45 stores, indicating the type and size of store.
2.	train - This is the historical training data, which covers to 2010-02-05 to 2012-11-01. 
3.	test - This file is identical to train.csv, except the weekly sales. 
4.	features - This file contains additional data related to the store, department, and regional activity for the given dates.

Link

https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting/overview



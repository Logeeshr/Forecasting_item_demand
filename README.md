# Item Demand Forecasting to Maximize profit and Minimise lose
#### Demand forecasts are fundamental to plan and deliver products and services. Accurate forecasting of demand can help the manufacturers to maintain appropriate stock which results in reduction in loss due to product not being sold and also reduces the opportunity cost (i.e. higher demand but less availability => opportunity lost). Despite such relevance, manufacturers have difficulty choosing which forecast model is the best for their use case. In this project, historical sales data corresponding to multiple(25) items sold in 10 stores are provided and participants are expected to come up with a best model to predict the future demand for products which results in maximum profit for the manufacturer.Predict the demand for the next 3 months at the item level (i.e. all the stores combined).


## Dataset
##### The dataset used is given by Guvi for Educational Purposes
##### The columns in the dataset
1. Date  -----> Date on which the items are sold
2. Store -----> Store on which Items are sold
3. Item  -----> 50 unique Items
4. Sales -----> Sales of every Item

## Workflow
1. Imporing Libraries
2. Data Wrangling
3. Exploratory Data Analysis
4. Feature Engineering
5. Model Building
6. Evaluation metrics

## About Project
##### In this project, the main aim is to predict the next 3 month Sales on item level from a particular Date. So I found the rolling sum for a window 90 days and predicted the Sales.In Model Building I used Decision tree Regressor, Random Forest Regressor, Linear Regression, XG Boost, KNN Regresoor are used. In that XG Boost performed well Compared to other model.






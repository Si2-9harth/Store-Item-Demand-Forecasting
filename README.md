# Store-Item-Demand-Forecasting
Time Series Analysis along with Boosting algorithms and Neural Networks to predict the store item demand for 13 weeks by analyzing and training on the dataset which consists of 5 years of sales on 10 stores containing 50 items.

1. Evaluation Criteria: Symmetric Mean Absolute Percentage Error.
2. Weekly Store Sales
![image](https://user-images.githubusercontent.com/98142436/162167031-f8ed6204-e76f-4a75-a1fd-c691d5f2db11.png)
3. Weekly Item Sales
![image](https://user-images.githubusercontent.com/98142436/162167173-74ddfc65-cd32-4e75-836f-b9574052c24f.png)
4. Dynamic Time Warping is being done to cluster the items to their respective quartile in the sales trend.
5. ARIMA model is being trained and predictions are taken from clustered and unclustered weekly data which gave similar results.
6. XGBoost Model was being used which gave better performance than ARIMA.
7. Neural Network model was built by including Batch Normalization for robustness which performed the best among the models.

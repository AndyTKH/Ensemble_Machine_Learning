# Daily Stock Returns Prediction using Random Forest and Boosting model 

In this project, we will generate daily returns for Apple stock (AAPL), using the previous day of lagged returns data. In this notebook, we will download 6 years worth of AAPL prices from Yahoo Finance and convert them into return series. Then, we will train Random Forest and Boosting model with previous day of lagged returns data for today's daily return prediction. To measure the performance of the model, we plot the mean squared error (MSE) of each method that looks like below: 

<img src='image/news.png' width=100% />

## Project Instructions

### Instructions

1. Open your terminal and clone the repository, then navigate to the the project folder.
```
git clone https://github.com/AndyTKH/Ensemble_Machine_Learning.git                                                          
cd Ensemble_Machine_Learning
```
2. Open the notebook to view the project. 
```
jupyter notebook ensemble_stock_prediction.ipynb
```
3. Simply close the terminal window to exit Jupyter Notebook. 

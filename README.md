# Project-MLDM


import pandas as pd


### Data
(path needs to be changed)


#### calendar

calendar = pd.read_csv("/Users/Xianghao/Desktop/M5/calendar.csv")
calendar.head()
calendar.info()


#### sell_prices

sell_prices = pd.read_csv("/Users/Xianghao/Desktop/M5/sell_prices.csv")
sell_prices.head()
sell_prices.info()


#### sales_train

sales_train_validation = pd.read_csv("/Users/Xianghao/Desktop/M5/sales_train_validation.csv")
sales_train_validation.head()
sales_train_validation.info()

sales_train_evaluation = pd.read_csv("/Users/Xianghao/Desktop/M5/sales_train_evaluation.csv")
sales_train_evaluation.head()
sales_train_evaluation.info()

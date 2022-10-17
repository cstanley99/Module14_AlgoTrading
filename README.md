# Module14_AlgoTrading

The following models use emerging market returns to build automated trading strategies based on short term and long term simple moving averages.

The base model has a short term window of 4 days and a long term window of 100 days with a 3 month training period







Increasing the training period to 6 months from 3 months increased overall returns to 1.8 from 1.5


![6_month_training](https://github.com/cstanley99/Module14_AlgoTrading/blob/main/6_month_training.png)

Changing the short SMA window to 20 from 4 and changing the long SMA window to 150 from 100 decreased overall returns to 1.25 from 1.5

![SMA20_150](https://github.com/cstanley99/Module14_AlgoTrading/blob/main/SMA20_150.png)

Decision Tree Classifier

![DTC_plot](https://github.com/cstanley99/Module14_AlgoTrading/blob/main/DTC_plot.png)

The Decision Tree Classifier showed nearly indentical returns to the base model

The only model that outperformed the base model was the "tuned" model which increased the training set to 6 months from 3 months.

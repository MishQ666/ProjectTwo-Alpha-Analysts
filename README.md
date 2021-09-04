# Alpha Analysts
#### Authored by: [Jenny](https://github.com/jennyntd), [Michelle](https://github.com/MishQ666), [Scott](https://github.com/Bomegolf), and [Thapa](https://github.com/TribThapa)


## Project Overview
Our project aimed to determine BUY-SELL signals for any stock listed on the US Stock Exchange using Time-series analysis. 

<p align="center">
    	<img src="https://techcrunch.com/wp-content/uploads/2019/06/GettyImages-1051659174.jpg?w=730&crop=1" width="1000">
</p>


*General Advice Warning*
*Information published on this website has been prepared for general information purposes only and not as specific advice to any particular person. Any advice contained in this document is General Advice and does not take into account any person’s particular investment objectives, financial situation and particular needs.*

*Before making an investment decision based on this advice you should consider, with or without the assistance of a qualified adviser, whether it is appropriate to your particular investment needs, objectives and financial circumstances.  Past performance of financial products is no assurance of future performance.*

*Due to time limitation, we are focusing on Amazon only for demonstration purpose.*


## Project description

- TimeSeries analysis was used to determine stock price 5-days moving forward

<p align="center">
    	<img src="/Image/ARIMA_Table.JPG" width="300" height="400">
</p>


<p align="center">
    	<img src="/Image/Forecast.JPG" width="800">
</p>


- MACD indicators were used to determine bullish or bearish movement in the market to reflect stock price strengthening or weakening 

![TradeSignal](https://github.com/MishQ666/ProjectTwo-Alpha-Analysts/blob/main/Image/AMZN_MACDSig_Indv.JPG)

- Here, is that [MACD App](https://drive.google.com/drive/folders/1abuvNk-AlsIswHqVwza9GbKKlGb1UYDL) you can use to determine your BUY-SELL signal for any stock listed on the US Stock Exchange.


Besides, we also used Classification and Regression machine learning models to train and predict stock prices:

Regression models:
- Regression
- Linear Regression
- Random Forest
- Extra trees
- Lasso Regression
- Ridge Regression
- Stochastic Gradient Design

In summary, all R squares have a negative value in the models selected above, indicating that the Regression models does not follow the trend of the data, so fits worse than a horizontal line. It is usually the case when there are constraints on either the intercept or the slope of the linear regression line.


<p align="center">
    	<img src="/Image/ML_Reg_Table.JPG" width="1000">
</p>
 
Classification models:
- Classification
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier
- Ada Boost Classifier
- XGBoost Classifier

In summary, for all Classification models we have low recall and precision values. This suggests, on average, our Classification models would be ~65% accurate which is not good enough to determine BUY-SELL signals when trading.


<p align="center">
   	<img src="/Image/ML_Class_Table.JPG" width="1000">
</p>



## Conclusion

In conclusion, MACD prices are good indicators to generate BUY-SELL signals. However, other metrics such as Relative Strength Indicator (RSI) and Fibonacci indicators should also be considered when making an informed decision to trigger a BUY or SELL.

## Sources
- [Google Colab](https://drive.google.com/drive/folders/1abuvNk-AlsIswHqVwza9GbKKlGb1UYDL)
- [ScikitLearn](https://scikit-learn.org/stable/)
- [Matplotlib](https://matplotlib.org/)
- [Pandas](https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html)
- [Yfinance](https://pypi.org/project/yfinance/)
- [Vectorbt](https://vectorbt.dev/)
- [Quantstats](https://www.youtube.com/watch?v=gsS3JxPXXvg)












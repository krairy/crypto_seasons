# Exploring crypto seasons

Explore Bitcoin and overall crypto seasonality patterns with methods of data science. 
---

![image](https://github.com/krairy/crypto_seasons/assets/48013494/bae6472e-4af6-4080-9ba2-c51ad90547b4)

Source: https://www.tradingview.com/chart/BLX/Rqj06lw7-Bitcoin-Seasons/

Bitcoin price seasonality is bound to two factors: the seasonality of the global economy and bitcoin halving events. The term halving refers to the reduction of mining rewards by a factor of 2, which is designed to gradually slow down the production of new bitcoins and make the resource more scarce, thereby boosting the price increase.

The chart above was created in the mid 2021 (at the border of the cyan shade). Orange lines mark the halving events, which are set to occur once in roughly 4 years (every 210,000 blocks). Estimation of the date of the last halving is outdated: the halving actually happened 19. Apr. 2024 about 9 am CEST.

The seasonality patterns - likely determined by eye - withstood the test of time quite well. But how well? And can they be utilized for price forecasting?

This chart inspired this - more formal - analysis of Bitcoin seasonality behavior.

Bitcoin price prediction
The goal of this analysis is:

To verify the chart above, i.e.
* EITHER confirm and reproduce the known seasonal patterns
* OR deny and find new seasonality behaviour
* To understand seasonal patterns of the first and largest cryptocurrency and build up an educated intuition
* Stretch goal: to build a predictive model for the price

# NAVIGATION
* [Exploratory analysis of Bitcoin price](https://github.com/krairy/crypto_seasons/blob/main/navigating-bitcoin-seasons-with-data-science.ipynb)
  
* [Tests of different NN architectures for price forecasting](https://github.com/krairy/crypto_seasons/blob/main/BTC_price_and_NN_zoo.ipynb)

* [Price forecasting with LSTM from Keras](https://github.com/krairy/crypto_seasons/blob/main/BTC_tds.ipynb)

# THIS IS A WIP

## Plan to try out: 
* ARMA family (SARIMA)
* GARCH
* XGBOOST
* LSTM - won't explain anything but will maybe make us money? :D (NO)

# THIS IS A FUN AND EDUCATIONAL PROJECT - NFA

# Backtesting
____________

[Backtesting](https://www.investopedia.com/terms/b/backtesting.asp) is the general method for seeing how well a strategy or model would have done [ex-post](https://www.investopedia.com/terms/e/expost.asp). 
Backtesting assesses the viability of a [trading strategy](https://www.investopedia.com/terms/t/trading-strategy.asp) by discovering how it would play out using historical data. 
If backtesting works, traders and analysts may have the confidence to employ it going forward.

<br>

## Simple Moving Average Indicator
A simple moving average ([SMA](https://www.investopedia.com/terms/s/sma.asp)) calculates the average of a selected range of prices, usually closing prices, by the number of periods in that range.

<br>

## Method
* If yesterday's closing price was on the line or below the SMA line, today we will open a long position
* If yesterday's closing price was above the SMA line, today we will open a short position
* The position will be closed when today's price closes

<br>

## Preparation
* Install [anaconda](https://www.anaconda.com/)
* Install packages numpy (!pip install numpy)
* Install packages pandas (!pip install pandas)
* Install packages requests (!pip install requests)
* Install packages tqdm (!pip install tqdm)
* Install packages sqlalchemy (!pip install sqlalchemy)
* Install packages matplotlib (!pip install matplotlib)

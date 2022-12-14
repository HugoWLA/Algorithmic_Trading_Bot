# Algorithmic_Trading_Bot
The Algorithmic trading bot is a bot that leanrs and adapts to new data and evolving markets by combining algorithmic trading skills
with financial Python programming and machine learning.

## Technologies

This project uses Python in addition several different add-ons, please make sure they are up to date.

* [pandas 1.4.3](https://github.com/pandas-dev/pandas/blob/main/README.md) - cv files and operations.

* [hvplot v0.8.0](https://qithub.com/holoviz/hvplot#readme) - interactive plots

* [numpy](https://https://numpy.org/) - Loaded in, not used in the framework, but could be used in future editions.

* [Matplotlib 4.0](https://matplotlib.org/) - For plotting graphs and charts that appear below the code.

* [scikit-learn 1.1](https://scikit-learn.org/stable/) - Tools for predictive Data analysis

## Performance Conclusions
The following image of our cumulative return plot shows actual returns vs. the strategy returns.

![cumulative return plot](images/cumretplot.png)

The following image is the first alternative plot. In this plot the data has been sliced into different periods. The time period has been
doubled from 3 months in the previous plot to 6 months. The conclusion for this adjustment is the selling predictions precision has been negatively
affected by 50%. I do not recommend this alternative adjustment.

![alternative image 1](images/alternative1.png)

The following image is the second alternative plot. In this plot the the trading algorithm has been modified by adjusting the SMA
input features. In this instance both windows where adjusted . "Short" from 4 to 30 and "Long" from 100 to 200. After reviewing the data 
and plot we can see that once again the selling precision has been affected negatively. Although the buy prediction precision is very high
ideally we would want a more balanced algorithm.

![alternative image 2](images/alternative2.png)

At this time our findings show that the original parameters worked best although i believe with more testing we would learn that
historically the more time and data available for the machine to learn the more accurate the algorithm becomes.

![cumulative return plot](images/cumretplot.png)

# License
[MIT](license)

## Contributers
Hugo Velazquez

linkedin.com/in/hugoghvelazquez


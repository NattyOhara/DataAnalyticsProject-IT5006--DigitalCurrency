Readme file:

#################
#####Team 12#####
#Scientist track#
#################

We included several csv files and ipynb files, in addition to the final report.
We'd like to explain how-to guide for our final outcomes.

FinalReport.pdf:
It's our final report. We summarize our whole project work into this final report.
So I appreciate you checking this file first.

DATACLEANING.ipynb:
the folder FINAL_DATASETS_29012021:
team12_cleandata.csv:
By this python notebook file, we implemented data gathering and preprocessing.
We gathered financial market data from different data sources and saved all raw csv data to the folder FINAL_DATASETS_29012021. Then, we ran DATACLEANING.ipynb such that we could create final clean dataset of team12_cleandata.csv. "team12_cleandata.csv" is used as the data infrastructure / database for whole projects.

ALLWORKS_IN_MILESTONE1.ipynb:
In this file, we included all preliminary exploratory research and analysis in milestone 1. Some of analysis includes incorrect analysis (such as applying regression to raw price data, not price % changes, and time-series analysis without the consideration of data stationarity) because we didn't learn those topic at that stage. However, for record keeping purpose and for illustrating our step-by-step understanding, we kept those analysis as well. You can reproduce the report of milestone 1 by this file.

LINEAR_REGRESSION.ipynb:
We implemented linear regression modeling in this file.

K-NN.ipynb:
We implemented prediction by K-NN classifier in this file.

TIMESERIES.ipynb:
We implemented time-series analysis and ARIMA model in this file.

EVENTSTUDY.ipynb:
We implemented event study in this file. Event study is our original implementation this time, so we explained what the event study is in this file, with actual coding and data example and implementation.

ARCH_GARCH.ipynb
With this file, we implemented another time-series analysis of ARCH and GARCH, to predict the volatility of cryptocurrency.
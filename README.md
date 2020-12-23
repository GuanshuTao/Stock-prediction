# Stock Price Predictor
- authors: Eric(Zhenrui) Yu, Guanshu Tao, William Xu
A data analysis collaboration project during the 2020 winter break.

## Introduction
For this project we are trying to answer the question: given the price history of S&P500 index, what is the price of S&P500 index today? Answering this prediction question is a good starting point because stock markets are hard to predict and we are interested in exploring whether the historical price plays an important role in future prices.

The data set used in this project is from Yahoo Finance and was sourced from Panadas Datareader[@pandas-datareader]. The timeline of the analysis is set from January 1, 2012 to December 17, 2020. Each row in the data set represents the daily performance of the S&P500, and each column represents an attribute of S&P500 (e.g., date, daily high, daily low, opening price, close price, volume, adjusted close price).

To be continued (3 more paragraphs):
Model planning

Some details of the model

Details of the evaluation of the model

Thus far we have performed some exploratory data analysis, and the report for that can be found [here](src/analysis.ipynb).

## Usage

To replicate the analysis, clone this GitHub repository, install the [dependencies](#dependencies) listed below, and run the following commands at the command line/terminal from the root directory of this project:

```
python src/download_data.py --ticker=^GSPC --data=yahoo --start=2012-01-01 --end=2020-12-17 --out_file=data/raw/SP500_data.csv
```

## Dependencies
- Python 3.8.6 and Python packages:
  - docopt==0.6.2
  - Keras==2.4.3
  - matplotlib==3.3.3
  - mplcyberpunk==0.1.11
  - numpy==1.19.4
  - pandas==0.24.2
  - pandas-datareader==0.9.0
  - scikit-learn==0.23.2
- R version 4.0.2 and R packages:
  - knitr==1.30
  - rmarkdown==1.25
  - reticulate==1.18
  - tidyverse==1.3.0

## License
The Stock Price Predictor materials here are licensed under the Creative Commons Attribution 2.5 Canada License (CC BY 2.5 CA). If re-using/re-mixing please provide attribution and link to this webpage.

# Reference

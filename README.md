---
output: 
  html_document:
    keep_md: true
---

## Stock Price Predictor
- authors: Eric(Zhenrui) Yu, Guanshu Tao, William Xu

## About

## Report

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


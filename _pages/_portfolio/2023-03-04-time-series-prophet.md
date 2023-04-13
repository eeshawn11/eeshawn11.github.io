---
layout: single
title:  Time Series Analysis with Prophet
date:   2023-03-04 10:00:00 +0800
permalink: /time-series-prophet/
excerpt: Time series forecast of Singapore's electrical demand using data scraped from the Energy Market Authority of Singapore.
tags: python kaggle pandas selenium prophet
---

Time series forecast using a [dataset](https://www.kaggle.com/datasets/eeshawn/half-hourly-electrical-demand-in-singapore) gathered from the [Energy Market Authority](https://www.ema.gov.sg/index.aspx) of Singapore. The original data is stored in individual weekly Excel files by month and year, which I have scraped from the website and combined into a dataset.

This is a relatively straightforward univariate time series problem involving electricity demand in Singapore and Prophet achieved a Mean Absolute Percentage Error (MAPE) of **3.67%** when predicting for demand in January 2023.

[![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/eeshawn/time-series-forecasting-with-prophet)

Skills Demonstrated:

- Extracting data through Web scraping with `Selenium`
- Data transformation with `pandas`
- Loading and storing data into `Kaggle` dataset
- Time series forecast with Facebook `Prophet`
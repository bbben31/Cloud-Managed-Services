# Cloud-Managed-Services



We want to build a system that streams stock pricing information for various stocks at different times and then notifies the stakeholders when the values cross specific points of interest (POIs).

We’ll use the Yahoo Finance APIs to query the running price of stocks and general information like 52-week high/low values.

Yahoo Finance API - It provides functions to download historical market data from Yahoo! finance. While this functionality in production would generally run on a paid api that provides real-time stock price data, we’ll mimic it by using historical data for an older time period and streaming it over kinesis.
Link - https://pypi.org/project/yfinance/

# Demand-Forecasting-for-Inventory-Management

Demand-Forecasting-For-Inventory-Management(DFIM) is a SARIMAX(Seasonal ARIMA) model used for detecting the open prices of a particular commodity in a 48 month period for predicting restocking schedules and costs.

## Pre-Requisites
- Python >= 3.6
- Scikit-image, Matplotlib, Numpy and Pandas

## Installation

Clone the repository onto your local machine using git:

```bash
git clone https://github.com/CNOSMohawks/Demand-forecasting-and-inventory-management-.git
```

## Overview

DFIM currently tries to predict the stock prices over the period of next 12 months, by data gained from the previous 36 months. It uses SARIMA - Seasonal ARIMA(auto regressive moving average) - as regular ARIMA does not perform well under seasons.

## Future Ideas

- Predict price more true to real life, i.e random noise and events in the prediction
- Lead up times for restock rescheduling with specified margins

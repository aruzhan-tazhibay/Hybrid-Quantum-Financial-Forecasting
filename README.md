# Hybrid-Quantum-Financial-Forecasting

This repository contains the dataset, training notebooks, and trained models (classical deep learning models, quantum neural networks, and hybrid quantum-classical architectures) for forecasting the S&P 500 index using binary classification, multiclass classification, and regression-based approaches.

---

## Repository Contents

### Dataset

The repository includes processed S&P 500 financial time-series data from 2021 to 2025 with technical indicators:

- Open
- High
- Low
- Close
- Volume
- SMA_50
- SMA_200
- RSI
- MACD
- Signal
- Momentum

---

## Trained Models

The repository includes selected best-performing trained models for:

- Binary classification
- Multiclass classification
- Regression forecasting

### Binary Classification Models

- BiLSTM
- CNN+GRU+QNN
- CNN+LSTM+QNN
- GRU+QNN
- LSTM+QNN

### Multiclass Classification Models

- BiLSTM
- CNN+GRU+QNN
- CNN+LSTM+QNN
- GRU+QNN
- LSTM+QNN

### Regression Models

- BiLSTM
- GRU+QNN
- LSTM+QNN
- QENN
- QSVM

---

## Repository Structure

```text
data/
    sp500_dataset.csv

models/
    binary classification/
    multiclass classification/
    regression/

training notebooks/
requirements.txt
```

---

## Data Source

Historical S&P 500 market data from 2021–2025 were obtained from Yahoo Finance using the yfinance API.

---

## Study Summary

The experimental results demonstrate that hybrid quantum-classical architectures outperform purely quantum and classical baseline models in financial time-series forecasting tasks.

The LSTM+QNN model achieved the best regression performance with:

- R² = 0.9407
- RMSE = 112.77
- MAE = 78.67
- MAPE = 1.32%

The study also demonstrates that regression-based forecasting is more suitable for trading-oriented financial applications than classification-based approaches.

---

## Authors

- Alibek Barlybayev
- Aruzhan Tazhibay
- Aizhan Nazyrova
- Alua Turginbayeva
- Nurgul Uzakkyzy
- Gulmira Shakhmetova
- Zhanar Lamasheva

Institute of Digital Sciences and Artificial Intelligence  
L.N. Gumilyov Eurasian National University  
Astana, Kazakhstan

---

## License

This repository is released under the MIT License.

---

## Citation

If you use this dataset or trained models in your research, please cite the associated publication.

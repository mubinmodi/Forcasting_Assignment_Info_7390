# Forecasting Crash Course

Video Link:  https://drive.google.com/drive/folders/1AYRZZW5_gfn0Zq3Ailg7mlK8Fipkh2pP?usp=sharing

A comprehensive Jupyter notebook teaching time series forecasting with ARIMA, SARIMA, and SARIMAX models through two practical examples.

## 📊 Overview

Learn forecasting from scratch with complete worked examples:
- **Example 1**: Airline passengers (monthly data, SARIMA)
- **Example 2**: Energy consumption (hourly data, SARIMAX)

## 🚀 Quick Start

### Installation
```bash
pip install numpy pandas matplotlib seaborn statsmodels scikit-learn scipy jupyter
```

### Run
```bash
jupyter notebook Forecasting_Crash_Course.ipynb
```

## 📚 What You'll Learn

- Time series fundamentals (stationarity, seasonality, trends)
- ARIMA/SARIMA/SARIMAX model building
- Parameter identification using ACF/PACF
- Model diagnostics and validation
- Business insights from forecasts

## 📦 Requirements

- Python 3.8+
- NumPy, Pandas, Matplotlib, Seaborn
- Statsmodels, Scikit-learn, SciPy
- Jupyter Notebook

## 🎯 Examples

### Airline Passengers (SARIMA)
- **Data**: 144 monthly observations
- **Model**: SARIMA(1,1,1)(1,1,1,12)
- **Performance**: MAPE < 5%
- **Use Case**: Capacity planning

### Energy Consumption (SARIMAX)
- **Data**: 1,440 hourly observations
- **Model**: SARIMAX with temperature
- **Performance**: MAPE < 10%
- **Use Case**: Cost optimization

## 📖 Structure

27 code blocks covering:
1. Setup & Theory
2. Data preparation
3. Model building
4. Diagnostics
5. Forecasting
6. Business insights

## 🤝 Contributing

Contributions welcome! Open issues or submit pull requests.

## 📜 License

MIT License - free to use and modify.


---

**Made with ❤️ for the Data Science Community**

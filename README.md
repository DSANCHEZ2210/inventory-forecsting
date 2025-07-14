
---

## Proyecto 2: `inventory-forecasting`

### README.md

```markdown
# Inventory Forecasting

Time series forecasting of weekly inventory levels for a pharmaceutical bottling machine (Electrolit) using deep learning and statistical models.

##  Objective
Predict one month of inventory needs using historical sales data to improve planning and reduce waste.

##  Tools & Libraries
- Python
- LSTM (Keras)
- Prophet (Meta)
- ARIMA (statsmodels)
- Pandas, Matplotlib, Scikit-learn

##  Results
- LSTM performed best on longer horizons (1 month)
- Prophet captured trend/seasonality very well
- Visual comparison of predictions vs real data included

##  Files
- `notebooks/`: model training and evaluation
- `forecast_plots/`: output graphs for each method

## 🔄 How to Run
```bash
jupyter notebook notebooks/LSTM_forecasting.ipynb

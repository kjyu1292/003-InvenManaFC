1. df-prod.ipynb: Segment product groups based on how much value each one brings back, and the rate being purchased
2. ts_forecast.ipynb:
- Process:
    + Preprocess: weekly grouping, add and fill in 0-value week
    + Choose product group to forecast, 'CX' in notebook
    + Hypertuning parameters of Holt-Winter Exponential Smoothing model
    + Concatenate two results from train and test to look at error distribution
- Current performance:
    + RMSE Train: 42.4987
    + RMSE Test: 31.9306

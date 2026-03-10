# Stock Price Movement Prediction

This project predicts whether a stock price will go up or down using Machine Learning.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn

## Features
- Data preprocessing
- Feature engineering (returns, moving averages)
- Logistic regression model

## Workflow
1. Load stock dataset
2. Calculate daily returns
3. Create moving averages
4. Train machine learning model
5. Predict stock movement

## Example Code

```python
df["Return"] = df["Close"].pct_change()
df["MA5"] = df["Close"].rolling(5).mean()

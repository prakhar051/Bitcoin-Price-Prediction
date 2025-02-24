# Bitcoin Next-Day Closing Price Prediction

## Problem Statement
Predict the next-day closing price of Bitcoin using historical price data.

## Approach
1. **Data Collection**: Historical price data for Bitcoin is obtained from the Kaggle dataset.
2. **Data Preprocessing**: The data is cleaned, normalized, and split into training and testing sets.
3. **Feature Engineering**: Past 60 days of closing prices are used as input features.
4. **Model Building**: An LSTM model is built using TensorFlow/Keras.
5. **Evaluation**: The model is evaluated using MAE and RMSE, and predictions are plotted against actual prices.

## Tools
- Python Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, TensorFlow/Keras
- Dataset: Top 10 Cryptocurrencies Historical Dataset from Kaggle
- Version Control: Git/GitHub

## How to Run the Code
1. Clone the repository: `git clone <repository-url>`
2. Install the required libraries: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook Bitcoin_Price_Prediction.ipynb`

## Future Improvements
- Hyperparameter tuning
- Incorporating additional features like sentiment analysis
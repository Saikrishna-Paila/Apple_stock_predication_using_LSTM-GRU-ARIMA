
## Team 4: Apple Stock Prediction
## Kaggle Link: https://www.kaggle.com/code/saikrishnapaila/apple-stock-prediction-using-rnn


### Members
- Saikrishna Paila

### Abstract
This project provides an in-depth analysis and time series forecasting model for Apple Inc.'s stock prices from July 1985, spanning 9765 trading days. The dataset includes pivotal moments such as iPhone and MacBook releases, showcasing Apple's innovative edge and market strategy. Our objective is to predict the closing stock price using a robust set of models and to assess the impact of major product launches and other significant corporate events on stock performance.

### Problem Statement
The financial market's dynamics are influenced by numerous factors, making stock price prediction complex but crucial. Our aim is to forecast Apple's stock price using sophisticated time series analysis techniques, encapsulating the trends and patterns from historical data.

### Dataset
The dataset spans from 1985 to 2024, covering nearly four decades of Apple's stock prices, including detailed dates of product launches such as 21 iPhone models and 25 MacBook models.

### Exploratory Data Analysis (EDA)
- **Pre and Post COVID-19 Impact Analysis**: Studied the fluctuations in Apple's stock price due to the global pandemic.
- **Product Launch Analysis**: Investigated stock price movements around the release dates of major products.
- **Seasonal Trends**: Identified seasonal trends in stock prices, correlating with product release cycles and holiday seasons.

### Models Implemented
1. **LSTM with XGBoost & Voting Regressor**
2. **LSTM with Lagged Features & Hyperparameter Tuning**
3. **LSTM with Transfer Learning**
4. **Prophet**
5. **LSTM without Lagged Features**
6. **ARIMA & SARIMA**

Each model employs different methodologies to capture and forecast the temporal dependencies within the stock data. The LSTM models, in particular, leverage time-dependent patterns, while ARIMA models address non-seasonal and seasonal aspects of the stock prices.

### Key Takeaways
- Major iPhone launches typically lead to stock price surges, while less popular models have seen declines.
- The transition to Apple-designed chips (M1, M2) significantly impacted stock values, underscoring market enthusiasm for technological innovation.
- Seasonal trends indicate higher stock prices during periods from September to December and January to March.

### Files
- `Team_4_Apple_Stock_Predication.ipynb`: Jupyter Notebook containing the code, analysis, and models for the project.
- `Team_4.pptx`: PowerPoint presentation summarizing the project findings and methodologies.

### How to Run
To replicate our findings:
1. Ensure you have Python installed with necessary libraries like Pandas, NumPy, Matplotlib, Sklearn, Keras, and FBProphet.
2. Download the Jupyter Notebook and run each cell sequentially to view the analysis and models in action.

### Acknowledgements
We thank all contributors and advisors who provided insights and feedback throughout the project.

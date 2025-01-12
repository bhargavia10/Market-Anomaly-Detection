# Market Anomaly Detection System

## About this Project
This project leverages XGBoost to train a machine learning model to predict stock market crashes. 
The model is backtested on data from Yahoo Finance and integrated into a Streamlit web-app that 
provides users a 5-prong investment strategy based on the market outlook.  

## Milestone 1: Model Development
- Selected Features: VIX, BDIY, USGG2YR, MXUS, DXY
- Feature Engineering: Moving averages, Rate of Change, Standard Deviation
- 94% precision and 99% recall for detecting Market Stable
- 94% precision and 59% recall for detecting Market Crash

## Milestone 2+3: Data-Driven Investment Strategy
- Backtested model using data from Yahoo Finance
- Streamlit Web-App for users to input custom values and obtain predictions
- OpenAI gpt-4 turbo to product investment strategy


**Forecasting Commitment of Traders Managed Money Positions for Agricultural Commodities**

In this project we build a supervised machine learning model to forecast the disaggregated report's managed money combined futures and options net position for CME corn. Although the analysis is specific to corn, the code is easily adaptable to any other agricultural commodity covered by the Commitment of Traders report. Being able to accurately forecast the speculative trader net position in a given futures market may significantly help guide one's own trading strategy.

**Key themes covered:**
- Introduction to Commitment of Traders report
- Cointegrated agricultural commodities
- Managed money flow
- Time series feature engineering
- Feature importance and feature selection
- XGBoost Regressor
- Hyperparameter tuning via Bayesian optimisation with Optuna
- One-step walk-forward model evaluation
- Residuals analysis (aka error analysis)

Please follow this [link](https://nbviewer.org/github/vzinkovski/forecasting_cot_managed_money/blob/main/forecasting_cot_managed_money.ipynb) to view the full project.

---

**Forecasting Commitment of Traders Managed Money Positions for Agricultural Commodities**

In this project we build a supervised machine learning model to forecast the disaggregated report's managed money combined futures and options net position for CME corn. Although the analysis is specific to corn, the code is easily adaptable to any other agricultural commodity covered by the Commitment of Traders (COT) report. Being able to accurately forecast the speculative money net position in a given futures market may significantly help guide one's own trading strategy.

**Key themes covered:**
- Introduction to the Commitment of Traders report
- Cointegrated agricultural commodities
- Managed money flow between equities and commodities
- Time series feature engineering
- XGBoost Regressor
- Feature importance and feature selection
- Hyperparameter tuning via Bayesian optimisation with Optuna
- Walk-forward model evaluation
- Using a naive forecast as the benchmark for model comparison
- RMSE and MAPE as performance metrics
- Residuals analysis (aka error analysis)

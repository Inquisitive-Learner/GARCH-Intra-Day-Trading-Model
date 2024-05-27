# GARCH-Intra-Day-Trading-Model Techniques
* GARCH model on the daily data.
* Predict 1-day ahead volatility in a rolling window
* Calculate prediction premium and form a daily signal from it.
* Merge with intraday data and calculate intraday indicators to form the intraday signal

![image](https://github.com/Inquisitive-Learner/GARCH-Intra-Day-Trading-Model/assets/80440978/55231586-d671-44d0-b90d-1e253a978219)

# Process
* Using simulated daily data and intraday 5-min data.
* Load Daily and 5-minute data.
* Define function to fit GARCH model on the daily data and predict 1-day ahead volatility in a rolling window.
* Calculate prediction premium and form a daily signal from it.
* Merge with intraday data and calculate intraday indicators to form the intraday signal.
* Generate the position entry and hold until the end of the day.
* Calculate final strategy returns.

Calculation of statistcs of strategy.

The python class performs calculation of some performance parametrs of the strategy. Methods of the class:

- Loads data
- Changes time format of column
- Renames columns and reformat dataframe to drop unnecessary columns
- Reformats dataframe to get information only about entry points into the trades
- Caluclates distance to stoploss at the time of entry into the trade
- Creates dataframe with data from entry and exit trades to calculate profit
- Displays statistics for both, Distance to stop-loss and Profit variations. The statistics is displayed for the whole available history and more detailed statistics of predefined periods corresponding to market cycles.

For strategies with stop-loss displayed statistics is:
Mean % of stop-loss
Standard deviation of stop_loss size
Maximum stop-loss
Minimum stop-loss For profit displayed statistics is:
Mean trade profit
Mean winnig trade trade
Mean losing trade trade
Gross profit
Gross loss
Risk/reward
Max win streak
Max lose streak
Total win trades
Total lose trades

Next improvements might me implemented:
- additional statistics of other take-profit levels
- calculation of performance with partial take-profits

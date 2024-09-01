# Moving Average Trading Strategy

Moving Average of short period is more closely associated with recent change of stock price, which we call Fast Signal. Moving Average over long period reflects the price change over long-term history, which we call slow signal. We create MA10 and MA50, which are fast signal and slow signal respectively. Then, we plot close price MA10 and MA50. If MA10 is larger than MA50, the stock price is believed by some traders, that it goes up in the next several days. Otherwise, the price will decrease. 
Our strategy is, if MA10 is larger than MA50, we will buy and hold one share of stock.

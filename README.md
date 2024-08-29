### For quick overview, click on - <a href="https://youtu.be/l4mfS_mQlGM">Project Demonstration</a>

# Algorithmic-Trading

Algorithmic trading, often referred to as Algo-trading, involves the use of computer programs to place trade at a very high speed and frequency which is impossible to replicate by any human trader. The main goal is to execute the instructions based on timing, price, quantity, or any mathematical model. It has significantly grown since the 1980s and is now used by institutional investors and large trading firms for various purposes. Here, one combines financial market knowledge with programming skills to create and manage trading algorithms.

But before exploring the intricacies, let's look at some basic hand-in-hand pros and cons.

## Benefits 
- No involvement of human emotions
- No Human Error as everything is automated
- Trades are timed correctly and instantly to avoid significant price changes
- Can be backtested on historical and real-time data to check the model

## Demerits 
- Since, it relies on historical data and mathematical models, any unforeseen market disruptions or black swan events, can incur significant losses
- Any technical issues or system failures can be fatal
- When heavy selling is performed by high-frequency traders in one or many securities, computer programs automatically react to these conditions. Thus, start selling large volumes of securities at an incredibly       rapid pace to avoid losses. As a result, the price continues to decrease and more benchmarks are triggered, causing a domino effect that sets off a sudden plunge in value.

<br>

# Equal-Weight S&P 500 Index Fund
Algo-trading is itself very vast, so covering everything is not an option. So, here I will be discussing about ***Equal-Weight S&P 500 Index Fund*** , a powerful indicator which everyone should know of.
I will be using Jupyter Notebook with Python and its libraries. 

The S&P 500 is the world's most popular stock market index that measures the stock performance of the top 500 large companies listed on stock exchanges in the US. It's widely regarded as one of the best indicators and is often used as a benchmark for the overall performance of the stock market. Several investors and analysts use this to track the health of the U.S. economy and make suitable investment decisions.
S&P 500 is the market capitalization (or size) weighted. Thus, the larger the company, the greater the weight in the index. It's not necessarily to be exactly 500 companies because some companies have multiple share classes also like Google-A, Google-C

But, I will be dicussing a variant of the widely-used S&P 500 index, which is "Equal Weight S&P 500". In this equal-weight version, each company in the index is allocated a fixed weight of 0.2% of the total index at each quarterly rebalance. 
- It provides a more balanced diversification by reducing concentration risk
- This approach can outperform when the smaller companies excel compared to the capital-weighted index
- The index is rebalanced quarterly to maintain equal weighting
  
<br>

## LICENSE
This project is licensed under the MIT License. See the [LICENSE](/LICENSE) file for details.

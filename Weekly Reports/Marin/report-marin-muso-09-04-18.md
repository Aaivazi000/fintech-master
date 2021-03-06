# Report Week 1

### The very beginning of weekly reports. There are no substantial goals or milestones to discuss, but there will be starting Week 2.

## Stretch Goals:

1. Establish a framework that can be used to measure the performance of the market and the performance of trading strategies. To do this, we can start by implementing well-known traditional strategies and applying well-known performance metrics on those strategies. These metrics will essentially serve as the basis for the framework to be used on new strategies in conjunction with the simulated market.

2. Use a RNN (or series of RNNs) to build the architecture of the generative part of the GAN. This includes modifying the financial data (specifically open, high, low, close, and volume) to feed into this part of the GAN. These may be two separate goals, but are bunched together for now.

## Goals for Week 2:

### Coordinate with Professor Punit to get 50GB data:
We have already scheduled time to meet with Professor Punit, so it is a matter of coordinating with him. We have OneDrive access all figured out, and as a last resort we have flash drive available.

### Set up an EC2 environment (or use some other provider):
Eventually we would like to compile our GAN architecture, and since none of us have access to computers with GPUs, a good resource is Amazon EC2. Amazon EC2 offers a free one year trial, and there are videos and other literature available for setting up an EC2 environment. We may also choose to use another provider, like Google if we no longer wish to use EC2.

### Implement a SMA/EMA trading bot:
The idea here is to implement a bot that uses SMA/EMA as its trading strategy. Eventually the bot will be allowed to trade on a dataset (S&P500 from 2013-2018, that we already own) for purposes of measuring the bots performance. The bot will be implemented in Python using NumPy, Pandas, and QuantLib. There is a Python port for QuantLib available so utilizing this module should not be an issue.

### Implement a function that can measure the Sharpe Ratio:
The goal is to start working on our framework for evaluation, and the Sharpe Ratio is a method for measuring a strategy's performance. This will play a roll in our overall framework and should be available to us as a function. We can implement the Sharpe Ratio using Python with NumPy and QuantLib.

### Implement a function that can measure the Sortino Ratio:
As with the implementation of the Sharpe Ratio, the Sortino Ratio is also a way of measuring a strategy's performance. This will play a roll in our overall framework and should be available to us as a function. We can implement the Sortino Ratio using Python with NumPy and QuantLib.

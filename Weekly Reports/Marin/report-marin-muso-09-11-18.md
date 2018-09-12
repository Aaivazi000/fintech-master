# Smart and Stretch Goals

**Name:** Marin Muso
**Date:** 09/11/18

## Stretch Goals (1-3)

## Stretch Goals:

1. Establish a framework that can be used to measure the performance of the market and the performance of trading strategies. To do this, we can start by implementing well-known traditional strategies and applying well-known performance metrics on those strategies. These metrics will essentially serve as the basis for the framework to be used on new strategies in conjunction with the simulated market.

2. Use a RNN (or series of RNNs) to build the architecture of the generative part of the GAN. This includes modifying the financial data (specifically open, high, low, close, and volume) to feed into this part of the GAN. These may be two separate goals, but are bunched together for now.

## S.M.A.R.T. Goals (next week)

### S.M.A.R.T. Goal 1.

#### S. Specific:
Gather historical technical data that goes further back than our current dataset. Our current technical dataset spans 5 years from 2013 to early 2018. This will be accomplished either by scraping the web or through coordination with Professor Punit.

#### M. Measurable:
If the data is to be scraped, then there will be scripts (either as .py files or .ipynb files) on Github that can prove this. Otherwise, if the data is provided by Professor Punit, then the data will be viewable through OneDrive or on a drive or used in some capacity.

#### A. Achievable:
We have access to OneDrive so it should be as easy as dragging and dropping, and as a backup we have a flash drive big enough for Professor Punit's dataset. Otherwise we can use BS4 and built-in Python modules to scrape the web for historical technical data.

#### R. Relevant :
Our dataset is very limited, so more data will help with both stretch goals above, and will serve us in the greater picture of the project.

#### T. Time-bound:
A meeting has been set for 09/12/18. Otherwise, we can start scraping as soon as possible after 09/12/18 and begin the process of collecting technical data.

### S.M.A.R.T. Goal 2.

#### S. Specific:
Research the use of RNN's, specifically with financial data, and compile a list of 5 or more sources with extensive summaries that can aid in the design and implementation of an RNN (which is later to be potentially used in a GAN).

#### M. Measurable:
The summaries along with the links to the sources will be uploaded on the Wiki. If any code is written, that will be linked as a .ipynb on GitHub.

#### A. Achievable:
There are videos on Lynda.com, DataCamp, and Safari that extensively cover RNN's. Google Scholar will also be used as resource for any journals or other peer-reviewed papers on the subject of RNN's. I have installed both PyTorch and TensorFlow on my machine to aid in the research of the RNN architecture.

#### R. Relevant :
It's important to start thinking about the generative part of the GAN. Since our data is timeseries data, it makes sense to try to use RNNs. This goal ties into Stretch Goal 2.

#### T. Time-bound:
A week is enough time to research RNNs.

### S.M.A.R.T. Goal 3.

#### S. Specific:
Apply the following metrics of performance on the 20D SMA and 20D EMA strategies that were implemented last week: volatility, rolling returns, maximum drawdown, sharpe ratio.

#### M. Measurable:
Graphs on a .ipynb will be provided on GitHub.

#### A. Achievable:
This is achievable With the use of NumPy and Pandas. The two strategies have already been implemented and formulas for the metrics have also been researched.

#### R. Relevant :
A portion of the project, although minor in comparison to other parts, is the evaluation of new strategies in comparison to existing strategies. It is imperative that we have an understanding of how current strategies are measured and how to perform those measurements. This serves Stretch Goal 1.

#### T. Time-bound:
A week is enough time to apply the metrics of performance on the two trading strategies.

### S.M.A.R.T. Goal 4.

#### S. Specific:
Implement the RSI trading strategy using the S&P500 dataset that we currently have access to.

#### M. Measurable:
The trading strategy will be available on GitHub as a .ipynb file.

#### A. Achievable:
This is achievable With the use of NumPy, Pandas, and QuantLib. Research on the strategy has already been conducted and it is only a matter of implementing it.

#### R. Relevant :
A portion of the project, although minor in comparison to other parts, is the evaluation of new strategies in comparison to existing strategies. It is imperative that we have an understanding of how current strategies are measured and how to perform those measurements. This serves Stretch Goal 1.

#### T. Time-bound:
A week is enough time to apply the metrics of performance on the two trading strategies.


## S.M.A.R.T. Goals (last week)

### Goal 1: Punit Data (On Hold)
We had originally set a meeting for 09/10/18, but due to the holiday had to reschedule the meeting for 09/12/18.

### Goal 2: Set up an EC2 environment (Success)
I started an EC2 server and wrote up some information on our server on the Wiki found here: https://github.com/shaf712/fintech-master/wiki/EC2 Full info on how to SSH into the server is not on the Wiki since the GitHub repo has not been privatized *yet* but is available upon request.

### Goal 3: SMA/EMA bots (Success)
The 20D SMA/EMA bots are implemented here: https://github.com/shaf712/fintech-master/blob/master/Marin%20Workspace/SMA.ipynb

### Goal 4: Sharpe Ratio (Success)
Fairly straight forward implementation of the Sharpe Ratio found here: https://github.com/shaf712/fintech-master/blob/master/Marin%20Workspace/sharpe.ipynb and Wiki article with a more in-depth analysis here:
https://github.com/shaf712/fintech-master/wiki/Sharpe-Ratio

### Goal 5: Sortino Ratio (On Hold)
On hold for now as we've decided on four measures of performance. Can easily be researched and implemented (and doesn't need to be a S.M.A.R.T Goal, it can just be something done in a matter of a few minutes).

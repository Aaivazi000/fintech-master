# Smart and Stretch Goals #

**Name:** Andriana Aivazians
**Date:** 09/11/2018

## Stretch Goals (1-3)

1. Fill in a stretch goal this are the big ideas that motivate your [part of the] project


## S.M.A.R.T. Goals (next week)


### S.M.A.R.T. Goal 1.

#### S. Specific: 
Write up a Literature Review on S&P 500 Trends and key characteristics. We need to know as much as we can about the index's performance because all the characteristics of the S&P 500 discovered must be found in our market simulations. There will be at the very least 5 reputable sources (online or printed) covering the topics below and any additional topics that are relevant:
* Annual & Seasonal Trends in the S&P 500, Macroeconoic Factors that contribute to S&P 500 performance
* Major historical events that affect the S&P 500 (elections, federal reserve meetings, etc)
* Identify common statistical measures of indexes (volatility, etc) and how they are taken.

#### M. Measurable: 
The review must have at least 5 reputable sources, with as many published papers as possible.

#### A. Achievable: 
The literature will utilize online resources including pulished papers and online articles (i.e investopedia). Published papers will be found using the CCNY databases, ACM libraries, and IEEE libraries.

#### R. Relevant :
The purpose of this research is to develop an understanding of key trends and qualities that are inherent to the S&P 500. This research will be used as the project continues to build the adversarial network in the GAN.


#### T. Time-bound: 
The deadline hard deadline for this goal is next week. However I would like to have it done by Thursday September 13th.

### S.M.A.R.T. Goal 2.

#### S. Specific: 
Utilize S&P 500 data from last semester to take measurements (daily, monthly, etc) of the index. The specific measurements will include volatility and other common ways stock indexes are measured (details to be found after completing Goal #1). The measurements taken will be collected into a dataset that will be used as input to the GAN. The goal is to take 5-10 measurments across different time periods (daily, weekly, monthly, yearly, etc) and to do this for at least 2 other indexes (NYSE, NASDAQ, DOW, etc).

#### M. Measurable: 
The python notebook created will have taken 5-10 index measurements of at least 3 stock indexes, one of which is the S&P 500. Along with the python notebook there will be a dataset exported from the notebook that holds all the measurments for the various indexes.

#### A. Achievable: 
Taking the measurments is possible because it will require simply Python skills and potentially the pandas library. This goal is also an opportunity to explore Quantlib, another library used for finanacial data that many have built-in functions that can be used to take the measurments of the different indexes.

#### R. Relevant :
Though this goal could be completed later on it is useful to take the time now to create additional datasets in advance, while we have the extra time. This dataset that will be made after completing this goal may be crucial inputs for both the generative and adversarial networks of our GAN. The point being if these measurments discover that S&P 500 volatility has never been greater than X then we need to ensure no market simulation we create will have a volatility greater than X. Hence we can train our GAN on this data.

#### T. Time-bound: 
The hard deadline for this goal is next week however I plan to have it completed by Friday September 14th.

### S.M.A.R.T. Goal 3: S&P 500 Feature Representation

#### S. Specific: 
Continue further research on CNNs, specifically those that are used on stock market data. The goal of this research is to report on the various was our group can convert our S&P 500 stock data into images that can be used as an input to a CNN. The goal will have two parts, research and implementation. The research part will be a report that identifies and explain at least 3 ways we can transform our stock data into images. Ideally we want a way to layer different features (open, close, open-close, moving averages, etc) onto one image. For the implementation the goal is to take at least 2 of the methods and convert a portion of our stock data into images using this method. Some topics to explore are Fourier Transforms, spectograms, stock charts, and candlestick charts.

#### M. Measurable: 
The research part of the goal will produce a report identifying and explaining 3 ways to transform stock data into images. The implementation part will produce a python notebook that implements 2 of the methods found in the research report using S&P 500 data we have on hand. The implementation may use index data or company-specific data, each of which we have access to.

#### A. Achievable: 
This goal is achievable since all the data required is available and I already have one method in which stock data was converted into an image and used in a CNN successfully (see GAN Resources Report on Github).

#### R. Relevant :
This goal is a continuation of research done in Week 1 (see GAN Resources Report on Github). In this report many of the sources used GANs on images and I believe it is worthwhile to continue with this idea to use CNNs in our GANs since there is a lot of literature available to rely on. Other group members are also exploring another path on how to use RNNs in our GAN.

#### T. Time-bound: 
The deadline for this goal is next week.


## S.M.A.R.T. Goals (last week)

1. Identify a list of 5-10 online resources (youtube videos, blog posts, papers, etc) that walk through how people implemented a GAN and/or MLP. Post the list to a markdown file on Github.
* The report can be found at this link: https://github.com/shaf712/fintech-master/tree/master/Andriana%20Workspace/Semester%202%20Week%201

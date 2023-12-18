# Probability_Project

## Background 
Given the backdrop of the Fed's interest rate hikes and the concurrent banking crisis, our team aim to delve into the performance of financial stocks and explore potential correlations between them.!

## Description of Data Set
The dataset comprises five stocks from the financial sector for analysis, namely Bank of America (BAC), BlackRock (BLK), J.P. Morgan (JPM), Kohlberg Kravis Roberts (KKR), and Nasdaq (NDAQ). The time range of dataset is from February 1, 2022, to June 30, 2023, which aligns with the U.S. interest rate hike cycle.

## Illustration of the Functionality of Jupter Notebook
- sigle_analysis. display_hist()
- sigle_analysis. display_qqplot()
- sigle_analysis. confidence_interval(confidence_level)
- sigle_analysis. regress_on_time()
- pair_analysis. ttest()
- pair_analysis. regression_on_another()

## Conclusion
1) All five stocks (BAC, BLK, JPM, KKR, NDAQ) conform to a roughly normal distribution and demonstrate no discernible regression relationship with time. This suggests that their observed returns align with typical statistical expectations and aren't noticeably influenced by time-related factors.

2) At a 95% confidence level, the computed confidence intervals for their population means fall within the range of -0.0027 to 0.0031, while for variances, they span from 0.00016 to 0.00057. 

3) Following a correlated t-test (confidence level=95%), there is an indication that their population means can be considered equal. It implies that investors may not expect significantly different average log returns from each stock.

4) The pair regression analysis reveals a positive correlation among these stocks. This indicates that when one of these financial stocks experiences a positive (or negative) movement, there is a tendency for the other to exhibit a corresponding pattern.




# Stable Alpha
The goal of this repository is to create a portfolio with equivalent risk and higher returns than the S&amp;P using quantitative, automated trading strategies

## Background
The S&amp;P 500 index fund is a widely accepted stable and long term investment. Due to the continued growth of US companies, it also yields decent annual returns and is often used a benchmark for judging other investments. Thus, investors in S&amp;P 500 index funds can take on a very passive role.

For investors seeking greater returns, however, alternatives are typically much more volatile and risky, thus requiring more active management. For example, investors in ProShares UltraPro S&amp;P 500 fund, which is a 3x leveraged ETF tracking the S&amp;P 500 index, experience 3x gains during periods of upturn, but also 3x losses during periods of downturn.

## Investment Thesis
To mitigate the volality of the ProShares UltraPro S&amp;P 500 fund, I propose identifying an indicator of significant downturns and automatically moving assets from the ProShares UltraPro S&amp;P 500 fund to stable assets like gold and bonds in the prescence of this indicator. 

One potential such indicator is short term, rapid downturn which will likely be followed by further losses. My work in the "Code" section will describe how I statistically verify and optimize this indicator.

## Trading Platform 
The trading platform I will be using is Composer. This online trading platform allows users to construct simple automated indicators for executing trades. Since I am limited in the types of indicators I can use, I decided to verify and optimize a conditional indicator of the following form: "IF MAX DOWNTURN OVER x DAYS > y%". If this conditional is satisfied, the platform will automatically trade all shares of the ProShares UltraPro S&amp;P 500 fund to the aforementioned stable assets. In particular, it will invest in: 25% GLD, 25% TIP, 25% IEI, and 25% BSV.

## Code
NEED TO COMPLETE 

## Performance
See backtested performance as compared to the S&amp;P 500 index fund and the ProShares UltraPro S&amp;P 500 fund on Composer: https://app.composer.trade/symphony/UmPd8GAt8sixWkBTfm9q

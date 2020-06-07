---
layout: default
title: Call Buy
parent: Call Strategies
permalink: /call-strategies/call-buy
---
# Call Buy <a href="https://twitter.com/share?ref_src=twsrc%5Etfw" class="twitter-share-button" data-text="Quick reference guide for #call buy #optionstrategy #optionnotes" data-url="http://optionnotes.com/call-strategies/call-buy" data-related="navdeepco" data-show-count="false">Tweet</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
- Buy call on a stock that you expect to rise in price
- Buying ITM call is better if stock will rise modestly
- OTM call is better for larger stock moves
- Time premium is highest for at the money call. Lowest for deep in the money/ out of money
- Rate of time decay accelerates as expiration approaches
- Buy higher delta calls for shorter timeframe :
    - Day trading ~ 0.90
    - 1-2 weeks ~ 0.80
    - Up to couple months ~ 0.50  
    
## When you have unrealized profit
- Do nothing - riskiest, might make more profit, might turn worthless by expiration
- Sell the call - safest, lock in your profit. Best if stock might fall back down. 
- Roll up - sell the current call, buy cheaper higher strike calls preferably after taking out the original investment. Highest profit if stock keeps rising, worst case 0 profit if stock doesn’t move or falls
- Bull spread - sell OTM call against the owned call, preferably with higher premium than original call. Profit if stock rises or stays same. Best if stock doesnt move

## When you have unrealized loss
- Consider rolling down and creating a bull spread. Sell the original call plus one more and use the proceeds to buy a lower strike call. This will require a smaller rebound in the stock to break even or make small profit than the original call. It will reduce the profit potential from unlimited since any gain in held long call will be offset by the sold short call.
- Calendar spread: sell a near term call with same strike as one help. Idea is, the short term call will expire worthless thereby reducing the overall loss. Risky, if the stock rallies before the near term expiry, this would result in both positions being in loss.
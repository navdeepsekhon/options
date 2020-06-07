---
layout: default
title: Ratio Call Spread
parent: Call Strategies
permalink: /call-strategies/ratio-call-spread
---
# Ratio Call Spread <a href="https://twitter.com/share?ref_src=twsrc%5Etfw" class="twitter-share-button" data-text="Quick reference guide for Ratio Call Spread #optionstrategy via #optionnotes" data-url="http://optionnotes.com/call-strategies/ratio-call-spread" data-related="" data-show-count="false">Tweet</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
- A neutral strategy that involves buying a number of calls at one strike and selling more calls at a higher strike
- Similar to a ratio write but has less downside risk and lower investment cost
- Has a range of profit
- 2:1 ratio call spread: buy one call at 10 strike, sell two calls at 15 strike
- Limited downside risk, unlimited potential upside risk, most profit if stock is exactly at the higher strike
- Max profit = initial credit + difference in strikes or difference in striker - initial debit
- Upside break even = higher strike + max profit
- Higher ratio = higher credit = lower downside risk
- Lower ratio = higher upside break even = lower upside risk

## Ratio spread as ratio write
- A deep in the money call can be substituted for the stock to simulate a ratio write
- If the call is at parity i.e. has no time value, the profit potential for spread will be same as ratio write
- Lower investment, lower downside risk
- One downside is, ratio writer will receive dividend, spreader won’t 
	
## Ratio spread for credit:
- One idea is to establish the spread with net credit
- In this case there is no downside risk. If the stock collapses you keep the credit
- There is still unlimited upside risk

## Delta spread:
- A completely neutral spread can be setup by using the delta of the calls involved
- Example, long call delta 0.80, short call delta 0.50, a ratio of 8:5 will be neutral.
- The idea with such a spread is to rely on time decay since the profit/loss will get cancelled by calls involved
- Avoid ratios greater than 4:1, too much upside risk 

## Follow ups:
- If the stock falls, the written calls can be rolled down. Not necessary if initial was credit 
- If the stock moves up, buy more calls to reduce the ratio

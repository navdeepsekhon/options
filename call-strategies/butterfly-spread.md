---
layout: default
title: Butterfly Spread
parent: Call Strategies
nav_order: 7
permalink: /call-strategies/butterfly-spread
---
# Butterfly Spread <a href="https://twitter.com/share?ref_src=twsrc%5Etfw" class="twitter-share-button" data-text="Quick reference guide for Butterfly Spread #optionstrategy via #optionnotes" data-url="http://optionnotes.com/call-strategies/butterfly-spread" data-related="" data-show-count="false">Tweet</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
- A neutral strategy involving a combination of both a bull spread and a bear spread
- Can be implemented using just calls, just puts or a combination of both
- Requires small investment, has limited risk and reward. Profits larger than potential risk
- There are four contracts and three strike prices involved in the spread
- Best when stock is near the middle strike; keep debit low
- Best butterfly spreads are found on more expensive/volatile stocks with strike prices 10-20 points apart

## Using only calls
- Buy one call at lowest striking price, sell two calls at the middle strike price and buy one call at the highest strike price
- Example: 
    - Buy 100 strike call for 12
    - Sell two 110 strike calls for 6 each
    - Buy 120 strike call for 3
- Spread will cost net debit of 3
- Max profit on expiration will be if the stock is at the short strike i.e. 100. In this case:
    - 100 strike will be worth 10 points (intrinsic value), 2 point loss
    - Two short calls will expire worthless, 12 point profit
    - 120 strike will be worthless, 3 point loss
    - Net 12 - 2 -3 = 7 point profit
- Max loss is limited to initial debit of 3
- Downside break even = lowest strike + debit
- Upside break even = highest strike - debit
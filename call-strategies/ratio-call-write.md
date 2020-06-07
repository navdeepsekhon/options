---
layout: default
title: Ratio Call Write
parent: Call Strategies
nav_order: 4
permalink: /call-strategies/ratio-call-write
---
# Ratio Call Write <a href="https://twitter.com/share?ref_src=twsrc%5Etfw" class="twitter-share-button" data-text="Quick reference guide for Ratio Call Write #optionstrategy via #optionnotes" data-url="http://optionnotes.com/call-strategies/ratio-call-write" data-related="" data-show-count="false">Tweet</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
- Combination of covered calls and naked calls
- Sell more calls than are covered by stocks owned. Example, 2 calls for 100 stocks owned
- Has two sided risk, if stock rises loss on uncovered call, if stock drops loss on the stock owned
- Downside protection equal to the premium from two calls, upside protection will be provided by rise in stock value
- Profit when stock remains within this up/down range
- High probability of limited profit
- Profit range should be wide enough in relation to volatility of stock and break even points should encompass next striking prices
- If support and resistance lie within range, stock is more likely to stay in range
- Could write calls out of money to be more bullish/bearish
- Another way is to alter ratio. More calls for bearish, more stocks  for bullish

## 2:1 ratio call
- Max profit  = strike - stock price + 2*call premium
- Downside break even = strike - max profit = stock price - 2*call price
- Upside break even = strike price + max price 

## Variable ratio call
- If stock price is midway between strikes, a regular 2:1 ratio call will not be neutral (same upside/downside range)
- In this case, sell one ITM and one OTM call. Max profit will result anywhere between the two strikes.
- Max profit is lower than regular 2:1 but has higher probability of max profit.
- Also called trapezoidal hedge
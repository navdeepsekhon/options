---
layout: default
title: Covered Calls (Buy Write)
parent: Call Strategies
permalink: /call-strategies/covered-call
---
# Covered Call (Buy Write) <a href="https://twitter.com/share?ref_src=twsrc%5Etfw" class="twitter-share-button" data-text="Quick reference guide for #coveredcall #optionstrategy via #optionnotes" data-url="http://optionnotes.com/call-strategies/covered-call" data-related="" data-show-count="false">Tweet</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
- Buy the underlying stock, sell a call on this stock. Treat these as a single unit.
- Use when slightly bullish or neutral on underlying. Do not use if bearish
- ITM call max profit = premium received. Reduced downside risk.
- OTM call max profit = premium + stock appreciation up to the strike price. More downside risk but potentially higher return
- ITM provides reduced downside risk (premium reduces cost basis). OTM offer potential higher return 
- In the money buy write calls make profit as long as stock doesn't drop below strike. Keep in mind the volatility, downside protection and ROI. Low beta stocks can work great
- ITM example: Buy XYZ at 50, sell 48 call for 3. Max profit if stock remains above 48. Some profit as long as price stays above 45 (48 - 3)
- OTM example: Buy XYZ at 50, sell 52 call for 2. Max profit above 52 = 2 premium + 2 stock appreciation

## Diversification

- Can diversify by selling at two different strikes.
- Combining ITM with OTM can improve return and downside protection
- Can all diversify across different expiration

## Protection from Stock price fall

- Consider rolling down instead of selling the stock.
- If the stock price falls, *rolling down* (buy back original call, sell another call with lower strike) can provide further downside protection 
- Roll down can lead to a loss-lock-in. If there’s a chance stock might rally back up, consider a rolling down only a portion of calls

## If the stock price rises

- Consider rolling up (buy back original call, sell higher strike call
- It will potentially increase the max profit but it will reduce downside protection
- The break even point will move up with the new call sale
- Rolling up to a distant expiry will require less money ( lower increase in break even)
- It could potentially lead to more loss if the stock falls back down (reduced downside protection )
- Increases risk

## At or near expiration

- For ITM call, if trading at parity, roll forward (replace with call in future)
- For OTM call, determine the per day $ premium for current call vs the future call
- It might be possible to roll up the OTM call in same expiry for more credit. Usually volatile stocks
- Let the stock be called if:
    - Rolling forward offer minimal return 
    - Rolling forward and up significantly reduces downside protection 
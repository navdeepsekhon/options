---
layout: default
title: Strangle
parent: Combined Strategies
permalink: /combined-strategies/strangle
---
# Strangle <a href="https://twitter.com/share?ref_src=twsrc%5Etfw" class="twitter-share-button" data-text="Quick reference guide for Strangle Option Strategy #optionstrategy via #optionnotes" data-url="http://optionnotes.com/combined-strategies/strangle" data-related="" data-show-count="false">Tweet</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

- Neutral strategy. High probability strategy. Sell one out of money call, sell one out of money put
- If you sell call and put with 0.16 delta i.e. one standard deviation away from current stock price, the trade has 70% probability of being profitable.
- Break even = put strike - premium received, call strike + premium received

## Defending the trade:

- Depending on risk tolerance, make adjustments to the trade either when:
    - stock price breaches the option strike price 
    - OR when price breaches the break even price
- Roll up: If the stock moves higher, buy back the current put and sell higher strike put. More premium will move break even higher, giving stock more room to rise
- Roll down: Same idea as above. If the stock moves lower, move the call down to get more credit
- Goal is to keep collecting premium so that stock remains within the break even point even if it has gone past the short option strike.

### Inverted Strange:
- If you keep moving the put up or the call down, at some point the strangle will go "inverted" i.e. put strike is now higher than call strike.
- This is ok, as long as we make sure that the total premium we collected is more than the difference between the two strike prices. For example:
    - say we start with 25 put and 75 call when the stock is at 50
    - stock keeps rising and we move the put all the way up to 75. So now we have a 75 call and put (btw this is called a [Straddle](straddle))
    - say upto this point we have collected $8 premium, that means if the stock stays below 83(75+8), we are fine
    - if the stock moves to 84, it is now outside of our break even point. We need to collect more premium
    - let's say moving the put to 84 will give us an extra $2, making total premium $10 and moving our break even to 85
    - From here, if the stock stays between 84-85, we profit at expiration because put will be worthless and we will have to buy back the call but it will be less than $10 (85-75)
    - If the stock goes between 75-84, now both our call and put will be in the money. **This is important** If the stock remain between this range, we will pay (84 - 75 = 9) at expiration to close our position. This is why it is important that we collect more premium than inverted strangle width.
    - If you can not collect enough premium, you can look to *roll out* your options i.e. sell farther dated options. It is good to roll out when the IV is high because that'll let you collect more premium
    - Sometimes when rolling out, you'd want to consider un-inverting the strangle or moving up/down the in the money side to bring the current stock price close to the center of your break evens.

<a href="https://github.com/navdeepsekhon/options/blob/master/combined-strategies/strangle.md">Edit page on GitHub</a>
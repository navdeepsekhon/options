---
layout: default
title: Poor Man's Covered Call (Synthetic Covered Call)
parent: Call Strategies
nav_order: 3
permalink: /call-strategies/synthetic-covered-call
---
# Poor Man's Covered Call (Synthetic Covered Call) <a href="https://twitter.com/share?ref_src=twsrc%5Etfw" class="twitter-share-button" data-text="Quick reference guide for Poor Man's Covered Call (Synthetic Covered Call) #optionstrategy via #optionnotes" data-url="http://optionnotes.com/call-strategies/synthetic-covered-call" data-related="" data-show-count="false">Tweet</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>


To execute a synthetic covered call (SCC) you buy a long-dated option, it works best with leaps in my experience, and sell an option with less DTE for a premium. If the stock price goes above your short call then you cover your position with your long call. If not you rinse and repeat. However, it is generally not profitable to let your short call expire in the money because the LEAP will have cost way more than the premium and differences between strikes. So we buy back the short call before it is in the money. Now you might think that since you had to buy back the short call for a loss that you lost money on this trade, but actually you'd be wrong. The spy LEAP we are long should have gained more value than the short call because they have almost no theta decay. So if the price of the stock moves up we remain profitable as long as we don't let our short call expire in the money. But let's think about what would have happened if the stock moved down? Well in that case the call we sold expires worthless and we get to keep the premium. Then the next week we can sell calls against our LEAP again. However, if there is a downward movement in the stock price than our LEAP is going to lose value as well. This is why you should only perform this strategy on a stock you are long term bullish on. (pretty much the same criteria that apply to searching for stocks to wheel applies here.) Much like in the wheel, our covered calls constantly reduce our price basis

Let's walk through an example on SPY. Spy is currently 309.10 The SPY January 2021 309 call is 20.99. The .30 delta strike for this Friday is 1.48. This means we can long the LEAP and short the 315 strikes for a net debit of 19.51. The best-case scenario for us would be for SPY to end the week at 314. If this happens we will get to keep the 1.48 premium we received and our LEAP will be worth approximately 23.73$ leaving us with a net profit of 1.48 + 2.74 = 4.22. Leaving us with a 21.6% return on our risk. (Our risk is 20.99 - 1.48 = 19.51) The worst-case scenario would be if SPY took a deep nose dive. In this case we would have to sell calls to reduce our cost basis much like you would on a wheel. However, since we are long term bullish on SPY (one of the requirements for this strategy) then we won't mind holding the LEAP and reducing our cost basis until SPY recovers.

### Why Use a SCC over a Covered Call Strategy?

I will again use our SPY example to demonstrate why the SCC is better than the CC. In our example, the max risk on the SCC was 1,951$ while if we were to use a covered call strategy we would have to risk $30,900. The max gain for a CC would be 315-309 = 6 + 1.48 = 7.48. Which is a 2.4% return on risk. Much less than our 21.6% return on risk for the SCC strategy. Now if you're really insistent on using 30,900$ on a SPY play then we really see how the SCC outperforms the CC strategy. You can perform approximately 14 SCC with the same capital as a CC. If the stock were to expire at 315 for the CC strategy you would make 722$ while if it were to expire at the 315 strike in the SCC strategy assuming you brought back the contract at 315 you would make approximately 111$ per spread * 14 spreads = 1554$.

### Managing A SCC Strategy

Rises in implied volatility are one of your biggest threats with this strategy. Performing this on something like SPY that is trading like a pharmaceutical company right now can be extremely risky because it can gap up 10$ or down 10$. Rises in implied volatility will also make it more expensive for you to buy back your short option while the price of the long option will stay roughly the same. When performing this strategy you want either falling implied volatility or volatility that is staying the same as when you sold your call. To combat this you need to be aware of the news surrounding the company beforehand. Don't play during earnings or other high IV events. If you are caught by surprise with rising IV it is best to buy back your short position and either hold your long position until IV decreases, sell your long position, or role your call to a higher strike.

Another thing to be aware of is a drop in the price of the underlying. If this happens and you are still long term bullish on the stock just sell more calls to reduce your price basis. If this is happening because of a change in the fundamentals of the company you want to close your position as fast as possible. (If this happens it may be tough to find volume on your LEAP so be aware of this.)


<a href="https://www.reddit.com/r/thetagang/comments/hcy0o1/why_synthetic_covered_calls_outperform_the_wheel/">Credits to original author on reddit</a>
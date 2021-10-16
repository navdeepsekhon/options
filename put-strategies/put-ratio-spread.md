---
layout: default
title: Front Put Ratio Spread
parent: Put Strategies
permalink: /put-strategies/put-ratio-spread
---
# Front Put Ratio Spread <a href="https://twitter.com/share?ref_src=twsrc%5Etfw" class="twitter-share-button" data-text="Quick reference guide for Front Put Ratio Spread Option Strategy #optionstrategy via #optionnotes" data-url="http://optionnotes.com/put-strategies/put-ratio-spread" data-related="" data-show-count="false">Tweet</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

- Neutral to slightly bearish strategy. Best for high IV when you expect stock to come down slightly.
- Buy 1 put, sell 2 put at lower strike. Example, buy one 50 strike put, sell two 40 strike puts
- Another way to think of it: It is a long put spread + 1 naked put
- Very high probability of profit when done for credit
- Example: If the above trade is opened for $1 credit then:
    - If stock doesn't move or goes up, you keep the $1
    - If stock moves down between 40-50, the long put spread becomes profitable + the original credit
- Great if the goal is to take stock assignment because the cost basis will much lower than if using just a short put

<a href="https://github.com/navdeepsekhon/options/blob/master/put-strategies/naked-put.md">Edit page on GitHub</a>
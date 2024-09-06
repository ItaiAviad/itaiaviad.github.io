+++
title = 'Reversal Strategy'
date = 2024-09-06T15:07:07+03:00
tags = [  ]
author = "Me"
showToc = true
TocOpen = false
draft = false
hidemeta = false
comments = false
description = "A Technical Analysis Reversal Strategy which utilizes price action"
canonicalURL = "https://canonical.url/to/page"
disableHLJS = true
disableShare = false
hideSummary = true
searchHidden = false
ShowReadingTime = true
ShowBreadCrumbs = true
ShowPostNavLinks = true
ShowWordCount = true
ShowRssButtonInSectionTermList = true
UseHugoToc = true

[cover]
image = "<image path/url>"
alt = "<alt text>"
caption = "<text>"
relative = false
hidden = true

# [editPost]
URL = "https://github.com/<path_to_repo>/content"
Text = "Suggest Changes"
appendFilePath = true
+++
# Strategy
This technical analysis reversal strategy utilizes support/resistance fakeouts, with other recommended technical analysis tools.
<!-- 1. [**Fakeout - Liquidity Grab**](#fakeout)
2. [**Entry**](#entry)
3. [**Improving the Strategy**](#improving-the-strategy)
   1. [**Candle Rule**](#ten-candle-rule)
   2. [**Divergence**](#divergence)
   3. [**Support/Resistance**](#support-resistance) --> -->

---
## Fakeout
### What is a Fakeout?
Fakeout is a term used in technical analysis to refer to a situation in which a trader enters into a position in anticipation of a future transaction signal or price movement, but the signal or movement never develops and the asset moves in the opposite direction. 

![Fakeout Example][fakeout-example]

### Using Fakeouts
![Fakeout Example 2][fakeout-example-2]
When a breakout occurs, a lot of traders will enter a long/short position (in the example above - a long). Those traders will set their **stop-losses** around the price of the breakout (in the example - below the support line, the red area).

In the case that the breakout was actually a fakeout, when the price reverses, it's going to hit all of the traders' stop-losses which will consequently move the price even more.

---
## Entry

Our entry point would be at the bottom/top of the candle that broke the support/resistance line.
![Entry Poitn Example][entry-point-example]

---
## Improving the Strategy

### Ten Candle Rule
On the **Daily** time frame, peaks closer together than 10 days saw a slightly larger compared to peaks larger apart.

![Ten Candle Rule][ten-candle-rule]

### Divergence
[Divergences](../divergence) give a stronger signal for a bulish/bearish reversal. It gives a higher probability of the strategy working in our favor.

### Support/Resistance
This strategy works best if you are finding reversals at the bottoms or tops of big moves.
Moving to a higher time frame is recommended in order to avoid false positives (1H, 4H etc.).
![big_support_ressistance_example][big-support-ressistance-example]

---
## Notes

This article is based on a Youtube video from the [TradingLab][trading-lab-channel] Youtube channel:
[I Reveal My Reversal Strategy [AMAZING]][trading-lab-reference-video]

---
## References

[Fakeout - Investopedia][investopedia-fakeout]


[entry-point-example]: /images/posts/trading/reversal_strategy/entry_point_example.png
[big-support-ressistance-example]: /images/posts/trading/reversal_strategy/big_support_ressistance_example.png
[trading-lab-reference-video]: https://www.youtube.com/watch?v=4cT8WTyxhYY
[trading-lab-channel]: https://www.youtube.com/@TradingLabOfficial
[fakeout-example]: /images/posts/trading/reversal_strategy/fakeout_example.png
[fakeout-example-2]: /images/posts/trading/reversal_strategy/fakeout_example_2.png
[ten-candle-rule]: /images/posts/trading/reversal_strategy/ten_candle_rule.png
[investopedia-fakeout]: https://www.investopedia.com/terms/f/fakeout.asp
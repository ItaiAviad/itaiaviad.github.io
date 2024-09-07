+++
title = 'FVG'
date = 2024-09-07T14:05:41+03:00
tags = [  ]
author = "Me"
showToc = true
TocOpen = false
draft = false
hidemeta = false
comments = false
description = "Fair Value Gaps"
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
## What is Fair Value?

Fair value is a measure of a product or asset's current market value and a reflection of the price at which an asset is bought or sold when a buyer and a seller freely agree. 

![Fair Value][fair-value-img]

## What is a Fair Value Gap?

A fair value gap is a brief inconsistency between a stock's current price and its fair value price, usually caused by a temporary imbalance between buyers and sellers.

![Fair Value Gap][fair-value-gap-img]

---
## Finding valid FVGs

### Unmitigated FVG

The FVG zone mustn't be "tested" for the FVG to be valid.

![Mitigated FVG][mitigated-fvg-img]


### FVG Reaction

The reaction of the candle inside the FVG should either **close inside** the FVG or to **close in the direction** of the zone.

![FVG Candle Close Inside](/images/posts/trading/fvg/fvg_close_inside.png)
![FVG Candle Close In Direction](/images/posts/trading/fvg/fvg_close_direction.png)


### Support/Resistance

Support/Resistance lines inside the FVG zone are great confluences and will raise the validity of the FVG.

![FVG Support/Resistance](/images/posts/trading/fvg/fvg_support.png)


### FVG Priority

Some FVG are stronger than others, and should be prioritized.

![FVG Priority](/images/posts/trading/fvg/fvg_priority.png)


### BOS (Break Of Structure)

![BOS](/images/posts/trading/fvg/bos.png)
There should be a BOS before the FVG is made for the FVG to be valid.
BOS|NO BOS
:---:|:---:
![FVG BOS](/images/posts/trading/fvg/fvg_bos.png)|![FVG NO BOS](/images/posts/trading/fvg/fvg_no_bos.png)

---
## Examples

![FVG Example](/images/posts/trading/fvg/fvg_example.png)

---
## Notes

This article is based on a Youtube video from the [TradingLab][trading-lab-channel] Youtube channel:
[I Found A Secret To Fair Value Gaps](https://www.youtube.com/watch?v=ZTMregh_428)

---
## References

[Fair Value - Investopedia][investopedia-fair-value]

[investopedia-fair-value]: https://www.investopedia.com/terms/f/fairvalue.asp
[fair-value-img]: /images/posts/trading/fvg/fair_value.png
[fair-value-gap-img]: /images/posts/trading/fvg/fair_value_gap.png
[mitigated-fvg-img]: /images/posts/trading/fvg/mitigated_fvg.png
[fvg-reaction-img]: /images/posts/trading/fvg/fvg_reaction.png
[trading-lab-channel]: https://www.youtube.com/@TradingLabOfficial

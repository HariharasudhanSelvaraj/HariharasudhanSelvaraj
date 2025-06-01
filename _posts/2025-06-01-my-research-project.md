---
title: "Are stock returns noramlly distrbuted?"
layout: single
author_profile: true
tags: [Exploration, Finance, statistics ]
---

## Assumptions are meant to be challenged. 

 Around 3000 BCE, people assumed the Earth was flat. They feared that if you traveled too far in one direction, you might just fall off. This assumption was not questioned until the 4th to 6th centuries BCE, where Pythagoras and Aristotle challenged the idea by showing empirical evidence that the Earth was actually round. Their discoveries opened the door for real exploration.

Fast forward to the 1800s, Neoclassical economists assumed that the economy would always bounce back to full employment because wages and prices are flexible, which meant there was no need for government intervention through fiscal policies. But that assumption had a price, the Great Depression, where an earlier government response could have softened the blow.

Today, billions of dollars change hands every day in the stock market, all under the assumption that returns are normally distributed. Not just investors and hedge funds, but banks and investment firms also rely on this assumption when calculating their worst case loss, the so-called Value at Risk.

But returns aren’t actually normal and infact as dataset increases to 30, 60, 90, and 120 points, returns are more and more not normal, which is true for daily, weekly, monthly, quarterly returns. I tested this myself on S&P 500 data from 1928 to 2025 using the Shapiro-Wilk test for normality. feel free to read the extended report attached below, along with the code, data, and excel files attached in the zip file at the bottom.

---

## View the PDF Document

<iframe src="/assets/Post_1.pdf" width="100%" height="600px" style="border: none;"></iframe>

---

## Download the Code

[Download ZIP of the code](../assets/Returns.zip)

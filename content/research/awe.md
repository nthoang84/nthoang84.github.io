---
title: "Added Worker Effect" 
date: 2025-03-01
lastmod: 2025-03-01
url: awe/
author: ["Hoang Nguyen"]
description: "This project documents empirical evidence of added worker effect (AWE) among US households using IPUMS Current Population Survey (CPS) microdata." 
summary: "Empirical evidence from CPS microdata reveals the added worker effect among US households: spousal labor supply rises when one partner becomes unemployed, especially among younger spouses." 

---

---

#### Download
+ [Code with replication instructions](https://github.com/nthoang84/added-worker-effect)

---

##### Project Description

Marriage offers an economic benefit by sharing risks through pooled resources and joint financial management. During economic challenges, having a partner serves as a safety net; if one partner faces illness or job loss, the other can provide support, reducing the overall burden. This risk diversification enhances family resilience. 

According to [Lundberg (1985)](https://www.jstor.org/stable/2535048), the added worker effect (AWE) refers to an increase in labor supply among spouses when one partner becomes unemployed. This project is inspired by similar studies of the AWE using CPS microdata including [Mankart and Oikonomou (2016)](https://doi.org/10.1093/restud/rdw055) and [Bacher, Grübener, and Nord (2025)](https://doi.org/10.1016/j.jmoneco.2024.103696).

I document that the likelihood of a spouse entering the labor force increases by 6.82 percentage points if the primary earner becomes unemployed compared to when the primary earner remains employed, confirming the existence of the AWE. I also run regressions to estimate the change in the probability that a non-participating spouse enters the labor force if the household head loses the job in two months, next month, this month, last month, or two months ago, relative to the baseline in which the household head remains employed. I find support for both anticipation and lagged effects, although spousal labor supply responses in the months preceding and following the primary earner's job loss are smaller than the contemporaneous response. When splitting the sample by spouse age, the contemporaneous AWE is positive and significant for younger spouses but disappears for older spouses, implying a strong age dependency of the AWE.


---


##### Acknowledgements

This project serves as my final assignment for *ECON 2020: Applied Economic Analysis*, taught by [Matthew DeHaven](https://matthewdehaven.com/) in Spring 2025 at Brown University. I thank the course instructor and my classmates for their helpful comments during the project proposal and presentation. Any remaining errors are my own.
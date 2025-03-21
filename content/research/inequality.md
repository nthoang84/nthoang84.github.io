---
title: "Wealth Inequality" 
date: 2025-03-01
lastmod: 2025-03-01
url: inequality/
author: ["Hoang Nguyen"]
description: "This project replicates macroeconomic models featuring heterogeneous agents and wealth inequality." 
summary: "Wealth in the United States is extremely concentrated—with the richest 1% of households owning one third of the total wealth. Two macroeconomic models of wealth inequality are replicated in an attempt to explain this phenomenon." 

---

---

#### Download
+ [Replication of Aiyagari (1994)](https://github.com/nthoang84/aiyagari)
+ [Replication of Cagetti and De Nardi (2006)](https://github.com/nthoang84/entrepreneurship)

---

##### Project Description

One standard assumption in macroeconomic models is that of complete markets—where agents have access to a sufficiently rich set of assets, ensuring wealth can be transferred across dates or states. However, empirical evidence rejects this view, leading to a focus on incomplete markets. [Aiyagari (1994)](https://doi.org/10.2307/2118417) introduces an incomplete-market model of heterogeneous agents with borrowing constraints in an environment with idiosyncratic, but no aggregate, risk. In this model, infinitely-lived agents face uninsurable income shocks and borrowing constraints that prevent them from fully smoothing consumption over time, forcing them to rely on precautionary savings. As a result, even when income is relatively evenly distributed, wealth accumulates in a highly skewed manner, leading to a distribution that is significantly more dispersed than income. I implement this model in C++ to replicate these results, using the Endogenous Grid Method as detailed in [Tomás R. Martinez's computational guide](https://tomasrm.github.io/teaching/quantmacro/aiyagari_comp.pdf).

[Cagetti and De Nardi (2006)](https://doi.org/10.1086/508032) develop a model of wealth inequality that distinguishes between entrepreneurs and workers, resulting in highly skewed wealth distributions. In this model, agents with higher ability who earn higher returns accumulate significant wealth. Entrepreneurial firms operate under decreasing returns-to-scale production functions, so higher entrepreneurial ability allows them to achieve a larger optimal scale. Because debt contracts are not fully enforceable due to limited commitment, business owners must use some of their assets as collateral, a portion of which may be seized if they default. As a result, entrepreneurs with promising projects have more at stake in the event of default, leading them to save more for collateral and borrow more to reach that larger scale. This process creates an extreme concentration of wealth at the top, particularly among entrepreneurial households. I replicate these results with a simplified version of this model that considers only young agents, thereby avoiding complications arising from Social Security payments and bequest incentives among old agents.


---


##### Acknowledgements

I thank [Professor Alexandre Gaillard](https://www.a-gaillard.com/) for his support, encouragement, and guidance in helping me understand and correctly implement these models. Any remaining errors are my own.
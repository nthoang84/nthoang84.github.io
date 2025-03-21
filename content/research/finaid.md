---
title: "College Financial Aid" 
date: 2025-02-10
lastmod: 2025-02-10
url: /finaid/
author: ["Andrew Samwick", "Hoang Nguyen"]
description: "This project analyzes college financial aid policies." 
summary: "This project examines the tradeoffs in college financial aid policies by highlighting how means-tested aid provides crucial insurance against income uncertainty while potentially creating moral hazards among student borrowers." 

---

---

#### Download
+ [Code for Insurance Value of Financial Aid](https://github.com/nthoang84/insurance-finaid)
+ [Code for Income-Driven Repayment Plan](https://github.com/nthoang84/income-based-repayment)

---

##### Project Description

Attending college is a key pathway to higher earnings, yet rising tuition costs make financing a major challenge for many families. Financial aid not only reduces these costs but also provides a safety net against income uncertainty by allocating aid based on both family income and assets. While this means-tested approach can discourage labor supply and saving, it also plays a critical role as an insurance mechanism that eases the financial burden when a family's income unexpectedly drops. This work seeks to better understand the incentives-insurance tradeoffs inherent in current college financial aid formulas.

[Fan, Fisher and Samwick (2025)](https://doi.org/10.1162/edfp_a_00442) develop a stochastic, life-cycle model that captures the challenges of income uncertainty, college financing, and retirement planning. Their analysis compares the traditional aid system with an alternative approach where colleges offer a direct tuition discount regardless of family wealth. This comparison highlights an important tradeoff: while a simple tuition discount might remove the saving disincentives of the current system, it would also take away a key insurance benefit that helps families during economic uncertainty. Inspired by their work, I implemented the model in C++ to replicate their results.

In adapting this theoretical framework to analyze the [Income-Driven Repayment (IDR) Plan](https://studentaid.gov/manage-loans/repayment/plans/income-driven), [Andrew Samwick](https://economics.dartmouth.edu/people/andrew-samwick) and I modified the model to account for the presence of a student loan at the start of one’s working life—whether repaid through a standard debt contract or an income-driven system—and to include the effort choices made by students during college and throughout their careers. We raised the possibility that the IDR Plan could induce moral hazard, with students potentially putting in less effort in college and choosing jobs with lower initial wages to reduce their repayment obligations.

Together, these projects shed light on the complex interplay between financial aid, family financial decisions, and student behavior. They highlight important tradeoffs in policy design—balancing the benefits of insurance against the potential for unintended incentives—and provide a framework for future research and policy discussions aimed at improving college affordability and access.

---


##### Acknowledgements

This work originates from my time as a research assistant under the guidance of Professor Andrew Samwick at Dartmouth College, beginning in the summer of 2021. I thank Professor Samwick for his constant support and encouragement. Any remaining errors are my own.
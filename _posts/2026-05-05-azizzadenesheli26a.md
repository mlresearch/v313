---
title: Reward Selection with Noisy Observations
abstract: We study a fundamental problem in optimization under uncertainty. There
  are $n$ boxes; each box $i$ contains a hidden reward $x_i$. Rewards are drawn i.i.d.
  from an unknown distribution $\mathcal{D}$. For each box $i$, we see $y_i$, an unbiased
  estimate of its reward, which is drawn from a Normal distribution with known standard
  deviation $\sigma_i$ (and an unknown mean $x_i$). Our task is to select a single
  box, with the goal of maximizing our reward. This problem captures a wide range
  of applications, e.g. ad auctions, where the hidden reward is the click-through
  rate of an ad. Previous work in this model ([Bax et. al, 2012]) proves that the
  naive policy, which selects the box with the largest estimate $y_i$, is suboptimal,
  and suggests a linear policy, which selects the box $i$ with the largest $y_i -
  c \cdot \sigma_i$, for some $c > 0$. However, no formal guarantees are given about
  the performance of either policy (e.g., whether their expected reward is within
  some factor of the optimal policy’s reward). In this work, we prove that both the
  naive policy and the linear policy are arbitrarily bad compared to the optimal policy,
  even when $\mathcal{D}$ is well-behaved, e.g. has monotone hazard rate (MHR), and
  even under a "small tail” condition, which requires that not too many boxes have
  arbitrarily large noise. On the flip side, we propose a simple threshold policy
  that gives a constant approximation to the reward of a prophet (who knows the realized
  values $x_1, …, x_n$) under the same "small tail” condition. We prove that when
  this condition is not satisfied, even an optimal clairvoyant policy (that knows
  $\mathcal{D}$) cannot get a constant approximation to the prophet, even for MHR
  distributions, implying that our threshold policy is optimal against the prophet
  benchmark, up to constants. En route to proving our results, we show a strong concentration
  result for the maximum of $n$ i.i.d. samples from an MHR random variable that might
  be of independent interest.
openreview: 22YAcqSAFO
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: azizzadenesheli26a
month: 0
tex_title: Reward Selection with Noisy Observations
firstpage: 1
lastpage: 34
page: 1-34
order: 1
cycles: false
bibtex_author: Azizzadenesheli, Kamyar and Dang, Trung and Mehta, Aranyak and Psomas,
  Alexandros and Zhang, Qian
author:
- given: Kamyar
  family: Azizzadenesheli
- given: Trung
  family: Dang
- given: Aranyak
  family: Mehta
- given: Alexandros
  family: Psomas
- given: Qian
  family: Zhang
date: 2026-05-05
address:
container-title: Proceedings of The 37th International Conference on Algorithmic Learning
  Theory
volume: '313'
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 5
  - 5
pdf: https://raw.githubusercontent.com/mlresearch/v313/main/assets/azizzadenesheli26a/azizzadenesheli26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

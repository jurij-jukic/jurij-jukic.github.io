---
title: "Home"
---

My name is Jurij (pronounced "Yuri").

My current goal is to create a static, predictive theory of training. Training seems to be governed by only a few variables (architecture, seed, data) with a lot of invariance across hyperparameters, seeds or datasets. 

My suspicion is that the way we currently do training is not computationally irreducible, but rather, given a better mathematical understanding of it, we could literally "skip" the training, predict the solution and jump straight to it. Whether this is possible or not, trying to answer that question will be informative.

We know that for adversarially constructed datasets, finding the optimal weights is NP-hard, but for most datasets, this may not be the case, and in fact, we have no a priori reason to believe that the current architectures are the best fit for the data.

So, why can't we predict the outcome of training?

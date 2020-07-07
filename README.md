# Parameter Estimation for a Wildfires Dataset


#### Description
---

The objective of this project was to implement a Markov Chain Monte Carlo Method for parameter estimation over a hierarchical model for a wildfires dataset. The dataset includes measurements of different attributes observed during wildfires such as temperature, wind speed, relative humidity, and the amount of rainfall. The Python program tries to uncover the joint probability distributions between each pair of features using Gibbs Sampling, which generates samples from the provided conditional distributions. After invoking Gibbs, MLE estimators of the multivariate gaussian parameters were calculated and additional burn-in time instantiations were tested to evaluate convergence of the generated Markov Chains.

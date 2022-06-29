# Privacy Preserving Inference on the Ratio of Two Gaussians Using (Weighted) Sums

This repo holds the [simulation](simulation.ipynb) used in paper

Jingang Miao, Yiming Paul Li. (2021). Privacy Preserving Inference on
 the Ratio of Two Gaussians Using (Weighted) Sums.
[arXiv:2110.15449](https://arxiv.org/abs/2110.15449).

To appear in the Journal of Data Science:
https://jds-online.org/journal/JDS/article/1281/info

Here is the abstract:

> The ratio of two Gaussians is useful in many contexts of statistical inference.
We discuss statistically valid inference of the ratio under Differential
Privacy (DP). We use the delta method to derive the asymptotic distribution
of the ratio estimator and use the Gaussian mechanism to provide (epsilon,
delta)-DP guarantees. Like many statistics, quantities involved in the
inference of a ratio can be re-written as functions of sums, and sums are
easy to work with for many reasons. In the context of DP, the sensitivity
of a sum is easy to calculate. We focus on getting the correct coverage
probability of 95\% confidence intervals (CIs) of the DP ratio estimator.
Our simulations show that the no-correction method, which ignores the DP
noise, gives CIs that are too narrow to provide proper coverage for small
samples. In our specific simulation scenario, the coverage of 95\% CIs
can be as low as below 10\%. We propose two methods to mitigate the under-coverage
issue, one based on Monte Carlo simulation and the other based on analytical
correction. We show that the CIs of our methods have much better coverage
with reasonable privacy budgets. In addition, our methods can handle weighted
data, when the weights are fixed and bounded.


## License
The majority of the project is licensed under CC-BY-NC;
however, portions of the project are available under separate license terms:
numpy and pandas are licensed under the BSD-3 license.

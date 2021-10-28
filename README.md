# Privacy Preserving Inference on the Ratio of Two Gaussians Using (Weighted) Sums

This repo holds the [simulation](simulation.ipynb) used in paper

**To be added**.

Here is the abstract:

> The ratio of two Gaussians is useful in many contexts of statistical inference.
We discuss statistically valid inference of the ratio
estimator under Differential Privacy (DP).
We use the delta method to derive the
asymptotic distribution of the ratio estimator and
use the Gaussian mechanism to provide
<img src="https://render.githubusercontent.com/render/math?math=(\epsilon, \delta)"> privacy guarantees.
Like many statistics, the quantities
needed here can be re-written as functions of
sums, and sums are easy to work with for many reasons.
In the DP case, the sensitivity of a sum can
be easily obtained.
We focus on the coverage of
95\% confidence intervals (CIs).
Our simulations shows that the no correction method,
which ignores the noise mechanism, gives CIs
that are too narrow to provide proper coverage for small samples.
We propose two methods to mitigate the under-coverage issue, one based on Monte Carlo simulations
and the other based on corrected variance terms.
We show that the CIs of our methods have the right coverage with proper privacy budget.
In addition, our methods can handle weighted data,
where the weights are fixed and bounded.


## License
The majority of the project is licensed under CC-BY-NC;
however, portions of the project are available under separate license terms:
numpy and pandas are licensed under the BSD-3 license.

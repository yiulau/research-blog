---
layout: post
title:  "Optimal acceptance rate for MCMC methods"
categories: jekyll update
---

Papers to pay attention to :

Roberts, G. O., Gelman, A. and Gilks, W. R. (1997). Weak convergence and optimal scaling of random walk Metropolis algorithms. Ann. Appl. Probab. 7 110–120.

Assumed density has product form. \\[f(\textbf{x})=\prod_{i=1}^pf(x_i)\\] Where 0.234 came from. Crazy math involving diffusion.


Gelman, A., Roberts, G. O. and Gilks, W. R. (1996). Efficient Metropolis jumping rules.BayesianStatist.5599–608.

Sister paper to the one shown above. Most theory comes from previous paper. Also mentioned measure of efficiency based on second eigenvalue of transition kernel. Simulations.

Roberts, Gareth O., and Jeffrey S. Rosenthal. "Optimal scaling for various Metropolis-Hastings algorithms." Statistical science 16.4 (2001): 351-367.

Some extension of Roberts 97 paper, still need density to be a density form. Some results for MALA and numerical simulations for when assumptions are not met.

Roberts, G. O. and Rosenthal, J. S. (1998). Optimal scaling of discrete approximations to Langevin diffusions. J. Roy. Statist. Soc. Ser. B 60 255–268.

Convergence results for MALA as well as some introduction to convergence for diffusions.

Brooks, Stephen P., Paulo Giudici, and Gareth O. Roberts. "Efficient construction of reversible jump Markov chain Monte Carlo proposal distributions." Journal of the Royal Statistical Society: Series B (Statistical Methodology) 65.1 (2003): 3-39.

Some acceptance rate results for reversible jump MCMC with connections to "Langevin algorithms" (MALA?). To read.

Beskos, Alexandros, et al. "Optimal tuning of the hybrid Monte Carlo algorithm." Bernoulli 19.5A (2013): 1501-1534.

Results for HMC.

Gupta, Sourendu, et al. "The acceptance probability in the hybrid Monte Carlo method." Physics Letters B 242.3 (1990): 437-443.

Where Neal's informal derivation of optimal acceptance rates for random walk MS and HMC comes from. More specifically, it contains derivation that relates acceptance probability to inverse CDF for normal distribution.

Note: to make Mathjax works, copy _layouts.
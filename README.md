# Bayesian-Statistics-Project
### *Content of the repository*
1) *Import_data.R* : the script contains functions to read data and to prepare the dataset for the analysis.
2) *Auxiliary_Functions.R* : the script contains several functions which performs repetitive tasks (e.g. computation of quantities for the full conditional, evaluation of some functions). In particular you can find the functions implementing the different versions of the Metropolis-Hastings step.
3) *Metropolis_within_Gibbs_v1.R* : in this script the MCMC simulation is performed using a Metropolis-within-Gibbs algorithm with coefficient of the warping functions computed as cumulative sum of S_l. Adaptive RWMH is employed here.
4) *Metropolis_within_Gibbs_v2.R* : in this script the MCMC simulation is performed using a Metropolis-within-Gibbs algorithm with coefficient of the warping function drawn from a Multivariate Gaussian.
5) *Results_and_Plots.R* : in this script the results produced in 3) are analyzed and the plots of the significant quantities are made.  

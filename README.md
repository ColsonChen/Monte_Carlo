# Monte_Carlo
## Monte_Carlo_Coursework_Projects

This repository contains the code in multiple languages to complete the coursework and projects for my Monte Carlo courses. 

The complete problem description may not be provided but a short summary of what was completed is listed as below

HW1:
- Random number generator with given parametric distribution (Cauchy & Logistic)
- Order statistics simulation using standard MC with full sample and MC with computed cdf 
- Box-Mueller method for random normal number generator with poor lattice properties (Showing the effect of lattice choices)
- Mean value method to estimate integral using standard MC
- Normal random generator with different method without vectorization
  - Box-Muller
  - Marsaglia's polar method
  - Rational approximation
  - Acceptance rejection 
  
HW2:
- Asian option pricing with standard MC, Log-normal approximation and Bachelier approximation
- CIR process simulation with Feller conditions assumption
  - Euler Scheme
  - Milstein Scheme
  - Modified Euler Scheme with approximation using Ito's lemma
- Option pricing under Heston Model with standard MC
- Option pricing under Jump diffusion model with standard MC

HW3:
- Variance reduction in Monte Carlo using Control Variates and Antithetic Sampling
- Variance reduction using conditional MC with Romano & Touzi's Formula
- Quasi Monte Carlo to evaluate expected value of cosine function of norms of random vectors
  - Standard MC
  - 1-Dimensional MC
  - Randomized Quasi Monte Carlo using Sobol set with Matousek scrambling

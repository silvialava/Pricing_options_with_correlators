This repository contains the code used for the paper:

Pricing Asian Options with Correlators

by Silvia Lavagnini

We derive a series expansion by Hermite polynomials for the price of an 
arithmetic Asian option in a one-dimensional setting. This series requires 
the computation of moments and correlators of the underlying price process, but 
for a polynomial jump-diffusion, these are given in closed form, hence no numerical 
simulation is required to evaluate the series. This allows, for example, for the 
explicit computation of Greeks. The weight function defining the Hermite polynomials 
is a Gaussian density with scale $b$. 
We find that the rate of convergence for the series depends on $b$, for which we 
prove a lower bound to guarantee convergence. Numerical examples show that the 
series expansion is accurate but unstable for initial values of the underlying process 
far from zero, mainly due to rounding errors. 

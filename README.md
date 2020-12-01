# Proximal Markov chain Monte Carlo algorithms
This work is carried out within the scope of an analysis of a research article, it is based on the article "Proximal Markov chain Monte Carlo algorithms" by Mr. Marcelo Pereyra.


## Introduction


Modern imaging methods rely strongly on Bayesian inference techniques to solve challenging imaging problems. While Monte Carlo algorithms have turned into standard tools over the past decade, they still face difficulties in handling inference for high-dimensional models. One of the main problems encountered when using MCMC in this settings is that it is difficult to design a Markov chain that efficiently samples the state space of interest.

This paper presents a new and highly efficient Markov chain Monte Carlo methodology to perform Bayesian computation for high dimensional models that are log-concave and non-smooth, a class of models that is central in image processing. The methodology improves the Metropolis-adjusted Langevin algorithm MALA using convex optimisation algorithms and proximal operators enabling us to capture local properties of the target density and explore the parameter space efficiently.


### Plan:-
#### Context:

          - Introduce: log-concave distributions, ULA and MALA.
          
          - Talk about convergence properties.
          
#### P-MALA: 
          - Introduce: Moreau-Yoshida approximation and its properties.
          
          - Introduce: P-ULA and P-MALA
          
          - Talk about convergence properties + proofs.
          
#### Applications.
          


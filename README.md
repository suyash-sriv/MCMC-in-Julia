# MCMC Methods in Julia

## Assignment 1:
Implement a Discrete Inverse Transform sampler for Poisson distribution.

Implement a Discrete Accept Reject Sampler to simulate draws from Binomial(n, p) using a Poisson proposal.

## Assignment 2
Prove that Barker's algorithm generates a Bern(cy*py/cx*px + cy*py) event. Also, find the probability distribution of the number of iterations it takes to give an output.

Sample uniformly from a p-dimensional sphere (a circle is p=2). Consider a p-vector x = (x1, x2, ... , xp) and let . denote the Euclidean norm. The pdf of this distribution is given. Use a uniform p-dimensional hypercube to sample uniformly from this sphere. Implement this for p = 2, 3, 4, 5, and 6. What happens as p increases?

Using accept-reject and a standard normal proposal, obtain samples from a truncated standard normal distribution. Run for a=4 and a=1. What are the differences between the two settings?

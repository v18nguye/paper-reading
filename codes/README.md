# June 2023

### Tutorial on MCMC sampling using Langevin Dynamics
[Link](https://abdulfatir.com/blog/2020/Langevin-Monte-Carlo/)

By given stochastic process, following a Langevin equation (Eq. 1),  which is defined by a potential function. We can apply FK equation to find the equilibrum distribution according to the potential function (Eq. 6). The Langevin equation can be written under SDE (Eq. 2), which can be further discretized with the Euler-Maruyama method (Eq. 8, 9).

### Riemann Geometry in ML (geomstats)
[Link](https://github.com/geomstats/geomstats)

- Computing in vector space:
    - Points, vectors, addition, subtraction.
    - Euclidean inner product, distance.

- Computing on a manifold:
    - Points, tangent vectors, exponential (to find a new point from the initial point with its tangent vector), logarithm (to find the initial tangent vector by using the end point and the inital one), geodesic (to find the path from the intial point to the end point with its tangent vector).
    - Riemannian metric, geodesic distance.
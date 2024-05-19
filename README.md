# Bayesian-model-for-DEM-calculations 

Discrete element method (DEM) is a way to estimate the motion of particles as they collide, employing Newton's second law. Although it can generally provide an accurate prediction of particles, such as microparticles and nanoparticles, it often requires small time steps and can easily become computationally expensive to handle. 

One way to simplify it is to use Bayesian Neural Networks, which are non-deterministic predictors and can predict distributions or probabilties.

In this problem, we are trying to use previous DEM runs to determine if two colliding particles stick or repell. The probability of sticking is defined by \alpha, ranging from 0 (non-sticking) to 1 (always sticking). alpha is a function of different surface properties of the particle, such as its surface charge, van der Waals attractive forces, and hydrophobicity. These are all the input parameters fed into the Bayesian NN to predict alpha


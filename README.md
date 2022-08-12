# Initialization-methods
Jupyter notebook file containing different methods of initialization of parameters for a multi-layer neural network.

"""… training deep models is a sufficiently difficult task that most algorithms are strongly affected by the choice of initialization. The initial point can determine whether the algorithm converges at all, with some initial points being so unstable that the algorithm encounters numerical difficulties and fails altogether.""""
- Yoshua Bengio, Deep learning

The file contains description for three different types of parameter initialization methods which are:

1. Zero intialization : Assign the values of the different parameters to zero.
2. Random initialization: Assign the value of w to random numbers. For b, we can keep the initialization to zero as it does not affect the performance a lot.
3. 'He' initialization: Use small values for the initialization of w. It increases the speed of computation, overcomes the problem of vanishing gradients, and increases the convergent nature of parameters for optimization. 

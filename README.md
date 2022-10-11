# Parareal
This is a short tutorial on the parareal algorithm as presented by Lions, Maday, and Turinici. It provides the implementation of the parareal algorithm for a 1D, first-order ODE. In addition, there is a simulator that provides a simulation of how the algorithm executes. More details are outlined in the preprint https://arxiv.org/abs/1706.08569. 

# parareal.jl
Provides an implementation of a basic parareal algorithm for a 1D, first-order ODE. It also includes a simulation that details how the algorithm works.

# parareal_tests.jl
Provides two test cases. The first converges quickly (in the eyeball norm) and is a case where the algorithm may provide speedup. The other converges very slowly, indicating a test case where parareal version will likely be slower than sequential algorithm.

# Maintenance Note
Give that Julia is a young language, this code may very well need minor changes in order to run. It should be compatible with Julia 0.7 at worst. 

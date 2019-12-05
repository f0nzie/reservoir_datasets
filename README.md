# README

Purpose of these datasets is using them for testing using [MRST](https://www.sintef.no/projectweb/mrst/) and its derivative in Pyhon using the machine learning library [PyTorch](https://pytorch.org/).

Since `PyTorch` has built-in functionality to work with  Graphics Processing Units or GPUs, we expect demonstrating that `PyTorch` GPU-based tensors could significantly reduce compute time during reservoir simulation.


## Evaluation for Proof of Concept
The steps are the following:

1. Find the Partial Differential Equations (PDE) that constitute the code of the MRST solvers.
    - Test the running times of the solvers using Matlab and Octave. Some code for testing is available in the latest book *An Introduction to Reservoir Simulation Using MATLAB, Octave* by Knut-Andreas Lie. See Appendix.
    - Code is being tested for performance under Matlab and Octave. Code will be published in a separate repository.


2. Replicate the functionality in Python using PyTorch for GPUs.
    - Convert the Matlab code to PyTorch
    - Measure the compute time of the original `MRST` solvers.


If the compute times are 10 to 100 faster in `PyTorch`, we will proceed with converting more Matlab code to PyTorch tensor based calculations.

## References
* This repository: https://github.com/f0nzie/reservoir_datasets

* [MRST](https://www.sintef.no/projectweb/mrst/)

* Book [An Introduction to Reservoir Simulation Using MATLAB, Octave* by Knut-Andreas Lie](https://www.cambridge.org/core/books/an-introduction-to-reservoir-simulation-using-matlabgnu-octave/F48C3D8C88A3F67E4D97D4E16970F894)






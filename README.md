# Masters
Detection of Covert attacks on cyber-physical systems using Markovian jump linear systems

This repository contains all Matlab algorithms I used during the development of my Master's thesis "Detection of Covert attacks on cyber-physical systems using Markovian jump linear systems". 

Here goes a list with their names and a short description of what each of them does:

1) Discretization: creates a discrete-time system from matrices of a continuous-time dynamic system model. I used it to discretize the quadruple tank model.
2) TND: generates elements similar to the elements of the original matrices through a Truncated Normal Distribution.
3) Eigenvalues: calculates the eigenvalues of a system. I used it to evaluate the stability of the obtained auxiliary system. The closer the eigenvalues are from 1, the less stable is the system.
4) Covert Detection: this is the final detection algorithm, it simulates the extended controlled system (composed by a cyber-physical system and the markovian auxiliary system), calculates the attacks signals and injects them into the extended system, runs the detection system and, finally, plots the results.

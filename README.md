# Display-Signal-Processing-using-Qiskit
Quantum Derivative Pricing using QSP

This repository contains the code for the construction of Polynomial Approximations for genrating Financial Payoffs on Quantum Computers. The language of choice is Qiskit and the circuits have been run on AerSimulator and ocassionally on GenericBackendV2(), the noisy backend of Qiskit.

For all intents and purposes, each of the notebook does what it is named after. The Circuits for European Call pricing and Autocallable Payoff may look the same. But the method of determining $\phi$ in both the cases are different, due to the choice of target function $f(x)$ for Minimax Optimization.

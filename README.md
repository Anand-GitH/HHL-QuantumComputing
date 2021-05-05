# HHL-QuantumComputing

Linear System Equations Solver using Quantum Computing (HHL Algorithm)
Quantum algorithm for solving linear systems of equations
Aram W. Harrow, Avinatan Hassidim, Seth Lloyd

Solving linear systems of equations is a common problem that arises both on its own and as 
a subroutine in more complex problems: given a matrix A and a vector b, find a vector x such that Ax=b

Quantum Phase Estimation is the key process for encoding the eigen values on to the circuit in the HHL algorithm.

Here we use both Amazon Braket and Qiskit inbuilt methods for demonstrating the Quantum Phase Estimation to derive eigen values of a matrix.
We also demonstrate - HHL using qiskit.

Created notebooks to demonstrate fundamentals of Braket Language, Quantum phase estimation and HHL 
1. Basics - Amazon Braket.ipynb
    Basics of Amazon Braket
    1. Braket language fundamentals
    2. Building quantum circuits
    3. Running on a simulator
    4. Processing results

2. QPE - QPE_AmazonBraket.ipynb - to find eigen values of unitary matrix using - Quantum Phase Estimation
3. QPE- Qiskit-QPEStandalone.ipynb - to find eigen values of any random matrix using - Quantum phase estimation with hamilitonion simulation using trotter method
4. UnitaryEvolution.pdf - explains how a non unitary matrix is converted to unitary approximation using hamiltonion simulation- trotter method
5. QPE-Qiskit-HHL.ipynb - shows how condition number of a matrix is responsible for the success of HHL algorithm





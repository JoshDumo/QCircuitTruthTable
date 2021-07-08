# QCircuitTruthTable
Obtaining truth tables from quantum circuits with classical gates

Basically realized that that classical circuits become so called Permutation matrices when represented in matrix form. This then means we check for only one 1 entry per column, and its location index is the circuit output.

In qiskit, the circuit matrix can be obtained from quantum_info

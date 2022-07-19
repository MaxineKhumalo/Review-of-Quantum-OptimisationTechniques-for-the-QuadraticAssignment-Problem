# Review of Quantum Optimisation Techniques for the Quadratic Assignment Problem

This repo contains the code used in Maxine Thembi Khumalo's MSc Computer Science project at the University of the Witwatersrand.

# What is inside this Repository
### Data

The .csv files from QAPLIB can be found in `/data/*`.

There are two types of data files; namely:

* Data from QAPLIB with the first three letters referencing the paper and a number giving the problem size (e.g. bur26a.csv is a dataset from a paper by R.E. Burkard with 26 locations.)
* Randomly generated data with the number referencing the problem size (e.g. made4.csv is a randomly generated matrix of size 4)

### Initial-points

These are paired to specific problem instances and used to improve the results of quantum heuristics implemented on quantum systems. All initial points used to generate results are listed.

### Some results files

This folder lists only a sample of quantum results. 

### Results.md

This file shows the summary of the results described in ***Solving the Quadratic Assignment Problem using Variational Quantum Eigensolver and Quantum Approximate Optimisation Algorithm***

# How to use

1. Select the method of choice
2. If it is a quantum heuristics method (the VQE and QAOA), install qiskit and generate an IBM Quantum Lab account. Enter the account details in the labelled cells.
3. Run the entire notebook and wait for the results files.
4. Use the "Test 30 trials" notebook to summarise the data (note classical methods' results have a different structure, and analysing those results is more trivial than quantum results)

# Device details

- \* In November 2021 the number of shots and circuits increased. Most measurements were taken with before this change. To understand the importance of throughput in quantum computing applications, read \href{https://research.ibm.com/blog/circuit-layer-operations-per-second}. 
- $\dagger$ Omitted Average CNOT Error values of decommissioned IBM quantum devices. Further details of these devices can be found \href{https://github.com/Qiskit/qiskit-terra/tree/master/qiskit/test/mock/backends}  and \href{https://quantum-computing.ibm.com/services?services=systems}.
    

## Specifications of the IBM Quantum Systems

| Quantum Device | Version | Available Qubits | Quantum Volume | Max Shots * | Max Circuits * | Processor Type | Average Readout Error | Average CNOT Error $\dagger$ | Online Date |  
|-----------------|--------|----|-----|------|-----|----------------|----------|----------|------------|
| ibmq\_guadalupe | 1.3.6  | 16 | 32  | 8192 | 900 | Falcon R4P     | 1.833e-2 | 1.041e-2 | 2021-01-08 |
| ibmq\_montreal  | 1.9.7  | 27 | 128 | 8192 | 900 | Falcon R4      | 2.067e-2 | 1.010e-2 | 2020-06-03 |
| ibmq\_sydney    | 1.0.37 | 27 | 32  | 8192 | 900 | Falcon R4      | 3.876e-2 | 1.291e-2 | 2020-09-02 |
| ibmq\_toronto   | 1.4.22 | 27 | 32  | 8192 | 900 | Falcon R4      | 4.253e-2 | 1.157e-2 | 2020-06-03 |
| ibmq\_mumbai    | 1.4.5  | 27 | 128 | 8192 | 900 | Falcon R5.1    | 3.887e-2 | 9.089e-3 | 2020-11-13 |
| ibm\_hanoi      | 1.0.0  | 27 | 64  | 8192 | 900 | Falcon R5.11   | 1.467e-2 | 1.237e-2 | 2021-04-24 |
| ibm\_cairo      | 1.0.0  | 27 | 64  | 8192 | 900 | Falcon R5.11   | 1.160e-2 | 1.039e-2 | 2021-05-20 |
| ibm\_auckland   | 1.2.8  | 27 | 64  | 10e5 | 300 | Falcon R5.11   | 1.158e-2 | 1.531e-2 | 2021-12-17 |
| ibmq\_manhattan | 1.19.1 | 65 | 32  | 8192 | 900 | Hummingbird R2 | 3.843e-2 | 1.541e-2 | 2020-07-24 |
| ibmq\_brooklyn  | 1.2.10 | 65 | 32  | 8192 | 900 | Hummingbird R2 | 2.546e-2 | 1.183e-2 | 2021-03-04 |

## Specifications of the  IBM Quantum Simulators

| Quantum Simulator | Version | Available Qubits | Noise Modelling | Max Shots | Max Circuits | Type | 
|------------------------|---------|-----|-----|------|-----|----------------------------|
| ibmq\_qasm\_simulator  | 0.1.547 | 32  | Yes | 8192 | 300 | General, context-aware     |
| simulator\_statevector | 0.1.547 | 32  | Yes | 8192 | 300 | Schrodinger's wavefunction | 
| simulator\_mps         | 0.1.547 | 100 | No  | 8192 | 300 | Matrix Product State       |

# References

- Burkard, R.E., Karisch, S.E. and Rendl, F., 1997. QAPLIB–a quadratic assignment problem library. Journal of Global optimisation, 10(4), pp.391-403.
- IBM Quantum. https://quantum-computing.ibm.com/, 2021
- Qiskit tutorials (since archived) https://github.com/MaxineKhumalo/qiskit-tutorials/tree/master/tutorials/algorithms


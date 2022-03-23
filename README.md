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

# How to use

1. Select the method of choice
2. If it is a quantum heuristics method (the VQE and QAOA), install qiskit and generate an IBM Quantum Lab account. Enter the account details in the labelled cells.
3. Run the entire notebook and wait for the results files.
4. Use the "Test 30 trials" notebook to summarise the data (note classical methods' results have a different structure, and analysing those results is more trivial than quantum results)


# References

- Burkard, R.E., Karisch, S.E. and Rendl, F., 1997. QAPLIB–a quadratic assignment problem library. Journal of Global optimisation, 10(4), pp.391-403.
- IBM Quantum. https://quantum-computing.ibm.com/, 2021
- Qiskit tutorials (since archived) https://github.com/MaxineKhumalo/qiskit-tutorials/tree/master/tutorials/algorithms


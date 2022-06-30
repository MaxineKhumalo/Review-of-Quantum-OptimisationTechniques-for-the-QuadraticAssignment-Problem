

# Data tables
The rapid development and sudden decommissioning of IBM Quantum systems, means that not all the QAP instances have results for all the $p$-values for the QAOA or all the problem sizes of the VQE.

- \* SR95: Success rate at 95\%
- $\dagger$ Feas.: percentage of trials found feasible
- $\ddagger$ Uncert: mean uncertainty percentage
- @ MT: average CPU time without outliers
    



## The VQE: solution quality and computational time results over problem size ($n$)

|$n$  | SR95* | Feas.$\dagger$| Uncert.$\ddagger$ | MT(s)@|  Devices|
|----|----|----|----|----|----|
|3| 100 | 100 | 95 | 33 | simulator\_mps   |
|3| 97 | 100 | 95 | 33 | simulator\_statevector   |
|3| 97 | 100 | 95 | 193 | ibmq\_qasm\_simulator   |
 |3| 23 | 100 | 0.44 | 150 | ibmq\_guadalupe  |
 |3| 87 | 100 | 0.77 | 653 | ibmq\_sydney   |
 |3| 30 | 100 | 0.49 | 587 | ibmq\_toronto  |
 |3| 83 | 100 | 0.51 | 266 | ibmq\_mumbai  |
 |3| 10 | 100 | 0.45 | 249 | ibm\_cairo  |
 |3| 47 | 100  | 0.42 | 1236 | ibm\_hanoi  |
 |3| 70 | 100 | 0.56 | 3072 | ibm\_auckland  |
|3 | 93 | 97 | 29 | 8106 | ibmq\_brooklyn  |
|4 | 97 | 97 | 98 | 36 | simulator\_mps   |
|4  | 100 | 100 | 95 | 38 | simulator\_statevector   |
 |4 | 97 | 97  | 98 | 184 | ibmq\_qasm\_simulator   |
|4  | 3 | 33 | 0.10 | 494 | ibmq\_guadalupe  |
|4  | 7 | 37 | 0.11 | 511 | ibmq\_sydney  |
 |4 | 3 | 30 | 0.10 | 582 | ibmq\_toronto  |
|4  | 3 | 56 | 0.10 | 266 | ibmq\_mumbai  |
|4  | 10 | 30 | 0.11 | 1160 | ibm\_cairo  |
|4  | 3 | 36 | 0.10 | 210 | ibm\_hanoi  |
 |4 | 6 | 16 | 0.10 | 252 | ibm\_auckland  |
|4  | 13 | 56 | 0.10 | 1439 | ibmq\_brooklyn  |
|5  | 0 | 96 | 94 | 316 | simulator\_mps   |
|5  | 0 | 96 | 94 | 57 | simulator\_statevector   |
|5  | 0 | 100  | 93 | 212 | ibmq\_qasm\_simulator   |
|5  | 0 | 0 | - | 2636 | ibmq\_sydney |
|5  | 0 | 3  | 0.10 | 1014 | ibmq\_toronto | 
|5  | 0 | 0 | - | 326 | ibmq\_mumbai  |
|5  | 0 | 0 | - | 1113 | ibm\_cairo  |
|5  | 0 | 3 | 0.10  | 276 | ibm\_hanoi  |
|5  | 0 | 0 | - | 311 | ibm\_auckland  |
|5  | 0 | 0  | - | 2170 | ibmq\_brooklyn  |
|6 | 0 | 100 | 84 | 835 | simulator\_mps |
|6  | 0 | 0 | - | 6654 | ibmq\_brooklyn  |
|7 | 0 | 96 | 1.1 | 1603 | simulator\_mps |
|7  | 0 | 0 | - | 13781 | ibmq\_brooklyn  |


## The QAOA: solution quality and computational time results over problem size ($n$) for each $p$-value

|$p$ | $n$ | SR95* | Feas.$\dagger$ | Uncert.$\ddagger$ | MT(s)}@|  Devices|
|----|----|----|----|----|----|----|
|1 | 3 | 23 | 100 | 4.1 | 445 | ibmq\_qasm\_simulator  |
|1 | 3  | 16 | 100 | 3.4 | 1768 | simulator\_statevector  |
|1 | 3   | 10 | 100 | 3.8 | 1956 | simulator\_mps   |
|1 | 3   | 16 | 100 | 2.6 | 2383 | ibmq\_guadalupe   |
|1 | 3   | 30 | 100 | 2.7 | 6595 | ibmq\_toronto   |
|1 | 3   | 60 | 100 | 2.3 | 2342 | ibmq\_montreal   |
|1 | 3   | 23 | 100 | 2.7 | 9713 | ibmq\_mumbai  |
|1 | 3   | 6 | 100 | 3.6 | 2863 | ibm\_hanoi  |
|1 | 3   | 10 | 100 | 2.5 | 5904 | ibm\_cairo  |
|1 | 3   | 23 | 100 | 2.4 | 19044 | ibm\_auckland  |
|1 | 3   | 16 | 100 | 2.8 | 12141 | ibmq\_manhattan  |
|1 |4    | 3 | 96 | 1.9 | 4729 | ibmq\_qasm\_simulator  |
|1 |4  | 33 | 100 | 0.17 | 5278 | simulator\_statevector |
|1 |4  | 30 | 96 | 0.12 | 7768 | simulator\_mps  |
|1 |4  | 20 | 100 | 0.21 | 7983 | ibmq\_guadalupe  |
|1 |4  | 20 | 90 | 0.17 | 6626 | ibmq\_toronto  |
|1 |4  | 43 | 100 | 0.18 | 28407 | ibmq\_montreal  |
|1 |4  | 23 | 96 | 0.17 | 8224 | ibm\_hanoi  |
|1 |4  | 30 | 96 | 0.17 | 9342 | ibm\_cairo |
|1 |4  | 10 | 100 | 0.20 | 9575 | ibm\_auckland |
|2 |3 | 20 | 100 | 3.6 | 2579 |  ibmq\_qasm\_simulator  |
|2 |3  | 36 | 100 | 3.4 | 1833 | simulator\_mps   |
|2 |3  | 13 | 100 | 3.7 | 1885 | simulator\_statevector   |
|2 |3  | 6 | 100 | 2.7 | 27097 | ibmq\_guadalupe   |
|2 |3  | 0 | 100 | 3.4 | 58853 | ibmq\_toronto   |
|2 |3  | 13 | 100 | 2.7 | 12043 | ibmq\_montreal  |
|2 |3  | 40 | 100 | 2.7 | 10608 | ibm\_hanoi   |
|2 |3  | 3 | 100 | 2.5 | 3137 | ibm\_cairo   |
|2 |3  | 60 | 100 | 4.0 | 1623 | ibm\_auckland   |
 |2 |4 | 10 | 86 |  0.21 | 6441 | ibmq\_qasm\_simulator  |
 |2 |4  | 16 | 90 | 0.21 | 9290 | simulator\_mps   |
|2 |4  | 20 | 96 | 0.18 | 5788 | simulator\_statevector    |
|2 |4  | 16 | 100 | 0.24 | 27322 | ibmq\_guadalupe |
|2 |4  | 13 | 96 | 0.22 | 29899 | ibmq\_toronto |
|2 |4  | 36 | 100 | 0.20 | 18789 | ibmq\_montreal  |
|2 |4  | 20 | 100 | 0.15 | 28250 | ibm\_hanoi |
|2 |4  | 13 | 100 | 0.19 | 21625 | ibm\_cairo   |
|2 |4  | 10 | 100 | 0.23 | 10521 | ibm\_auckland   |
|3 |3 | 26 | 100 | 0.47 | 221 | ibmq\_qasm\_simulator |
|3 |3  | 16 | 100 | 3.9 | 1990 | simulator\_mps   |
|3 |3  | 16 | 100 | 3.8 | 2160 | simulator\_statevector   |
|3 |3  | 3 | 100 | 2.2 | 10835 | ibmq\_guadalupe   |
|3 |3  | 20 | 100 | 0.40 | 46532 | ibmq\_sydney   |
|3 |3  | 0 | 100 | 0.30 | 453  | ibmq\_toronto  |
|3 |3  | 10 | 100 | 2.0 | 12581 | ibmq\_montreal  |
|3 |3  | 33 | 100 | 3.5 | 9517 | ibmq\_mumbai  |
|3 |3  | 13 | 100 | 2.1 | 12465 | ibm\_hanoi  |
|3 |3  | 13 | 100 | 2.0 | 31879 | ibm\_cairo  |
|3 |4  | 3 | 26 | 0.10 | 320 | ibmq\_qasm\_simulator |
|3 |4   | 13 | 96 | 0.12 | 11483 | simulator\_mps   |
|3 |4   | 26 | 93 | 0.12 | 6221 | simulator\_statevector   |
|3 |4   | 30 | 96 | 0.20 |  8347 | ibmq\_guadalupe   |
|3 |4   | 16 | 60 | 0.10 | 8325 | ibmq\_sydney  |
|3 |4   | 6 | 36 | 0.10 | 1446 | ibmq\_toronto  |
|3 |4   | 30 | 100 | 0.14 | 17426 | ibmq\_montreal  |
|3 |4   | 16 | 100 | 0.14 | 10254 | ibm\_cairo  |





## Quantum warm-start: the VQE and the QAOA solution quality and computational time results over problem size ($n$) (only 10 trials)

 |$n$ | $p$ | SR95* | Feas.$\dagger$ | Uncert.$\ddagger$ | MT(s)@ |  Devices | Method|
|----|----|----|----|----|----|----|----|
|3 | 1 | 0 | 100 | 7.8 | 1610 | ibmq\_qasm\_simulator | QAOA|
|3 | 1  | 10 | 100 | 2.4 | 1327 | simulator\_mps | QAOA|
|3 | 1  | 10 | 100 | 2.7 | 2095 | simulator\_statevector | QAOA|
|3 | 1  | 40 | 100 | 2.1 | 4509 | ibm\_cairo |QAOA |
|3 | 2 | 20 | 100 | 4.5 | 2070 | simulator\_mps | QAOA |
|3 | 2  | 10 | 100 | 4.6 | 2311 | simulator\_statevector | QAOA |
|3 | 2  | 10 | 100 | 2.2 | 3373 | ibm\_cairo |QAOA  |
|3 | 2  | 10 | 100 | 2.1 | 17869 | ibm\_hanoi |  QAOA|
|3 | 3  | 30 | 100 | 0.60 | 102 | ibmq\_qasm\_simulator | QAOA |
|3 | 3  | 20 | 100 | 3.5 | 1433 | simulator\_mps | QAOA |
|3 | 3  | 40 | 100 | 3.1 | 1147 | simulator\_statevector | QAOA |
|3 | 3  | 10 | 100 | 0.46 | 1346 | toronto | QAOA |
|3 | - | 100 | 100 | 1.1 | 153 | ibmq\_qasm\_simulator |  VQE |
|3 | -  | 90 | 100 | 1.2 | 147 | simulator\_statevector | VQE |
|3 | -  | 90 | 100 | 1.6 | 243 | simulator\_mps | VQE |
|3 | -  | 70 | 100 | 0.42 | 3889 | ibmq\_guadalupe |  VQE|
|3 | -  | 40 | 100 | 0.39 | 734 | ibmq\_sydney | VQE |
|4 |1 | 20 | 100 | 0.15 | 5394 | ibmq\_qasm\_simulator | QAOA |
|4 |1  | 30 | 100 | 0.14 | 6180 | simulator\_statevector |QAOA |
|4 |1  | 20 | 100 | 0.14 | 5989 | ibm\_cairo | QAOA |
|4 |2 | 30 | 100  | 0.12 | 8266 | simulator\_mps | QAOA |
|4 |2  | 20 | 100 | 0.16 | 5371 | simulator\_statevector | QAOA |
|4 |2  | 60 | 100 | 0.13 | 6857 | ibm\_cairo | QAOA |
|4 |2  | 30 | 100 | 0.11 | 18568 | ibm\_hanoi | QAOA |
|4 |3 | 0 | 20 | 0.10 | 133 | ibmq\_qasm\_simulator |QAOA  |
|4 |3   | 10 | 100 | 0.12 | 10954 | simulator\_mps |  QAOA|
|4 |3   | 20 | 80 | 0.15 | 5327 | simulator\_statevector | QAOA |
|4 |3   | 10 | 50 | 0.12 | 1703 | ibmq\_toronto | QAOA |
|4 |- | 0 | 0 | - | 238 | ibmq\_qasm\_simulator |  VQE |
|4 |-  | 0 | 90 | 0.10 | 273 | simulator\_mps | VQE |
|4 |-  | 0 | 0 | - | 320 | simulator\_statevector | VQE |
|5 |1 | 0 | 0 | - | 13411 | ibmq\_qasm\_simulator | QAOA |
|5 |1  | 0 | 0 | - | 11862 | simulator\_statevector | QAOA |
|5 |1  | 0 | 10  | 0.10 | 58487 | ibm\_cairo | QAOA |
|5 |1  | 0 | 0 | - | 54655 | ibmq\_mumbai | QAOA|
|5 |2 | 0 | 0  | - | 12177 | simulator\_statevector | QAOA |
|5 |2  | 0 | 40 | 0.10 | 17670 | ibm\_cairo |QAOA  |
|5 |2  | 0 | 10 | 0.10 | 45564 | ibm\_hanoi | QAOA |
|5 |3 | 0 | 0  | - | 359 | ibmq\_qasm\_simulator |  QAOA|
|5 |3  | 0 | 0 | - | 11859 | simulator\_statevector |  QAOA|
|5 |- | 0 | 0 | - | 226 | ibmq\_qasm\_simulator |  VQE |
|5 |-  | 0 | 0 | - | 235 | simulator\_mps | VQE |
|5 |-  | 0 | 0 | - | 265 | simulator\_statevector | VQE |

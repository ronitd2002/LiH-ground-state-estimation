## Using VQE to find ground state energy of LiH molecule with Parity Mapping and Qubit Tapering

Notebook files for the AMQIS (Atomic & Molecular Quantum Information Science) Term Project semester 6 2023 conducted by the Department of Physics, IIT Kharagpur.
---

In this semester term project, we provide the solution for estimating the energy of the ground state energy of the Lithium Hydride molecular system using Variational Algorithm. Upon optimization of the energy cost function using the quantum chemistry libraries of the IBM Qiskit framework using the SLSQP optimizer, we find that the solution obtained is sub optimal (based on validation from real molecular energy data in hartree units) and for further improvement we taper off required qubits based on point symmetres of the molecule and thus vastly improving our estimation results for the energy cost function. The results of our experiments are clearly described in the detail in the associated report while the experiements are deonstrated in the code section of this repository. 

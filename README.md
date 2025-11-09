# Qiskit Quantum Computing Practice Repository

A comprehensive collection of quantum computing practice problems, solutions, and implementations using IBM's Qiskit framework. This repository serves as a study guide for quantum computing concepts and IBM Quantum certification preparation.

## Overview

This repository contains Jupyter notebooks demonstrating fundamental quantum computing concepts and Qiskit implementations. Each question explores different aspects of quantum circuit design, measurement, and analysis.

## Contents

### Fundamental Concepts (Questions 1-4)

1. **Question 1: QASM Conversion** (`Question 1.ipynb`)
   - Converting quantum circuits to OpenQASM format
   - Understanding quantum assembly language representation
   - Working with quantum registers and classical registers

2. **Question 2: Circuit Depth Analysis** (`Question 2.ipynb`)
   - Calculating quantum circuit depth
   - Understanding parallel gate execution
   - Circuit optimization concepts

3. **Question 3: Qiskit Version Management** (`Question 3.ipynb`)
   - Checking Qiskit installation and versioning
   - Understanding Qiskit module ecosystem
   - Dependency management for quantum projects

4. **Question 4: Quantum Superposition** (`Question 4.ipynb`)
   - Hadamard gate and quantum coin flip
   - Creating equal superposition states
   - Measurement and probability distributions
   - Visualization with histograms

### Advanced Topics (Questions 5-6)

5. **Question 5: Quantum Entanglement** (`Question 5 - Quantum Entanglement.ipynb`)
   - Creating Bell states (maximally entangled states)
   - Understanding CNOT gates and two-qubit operations
   - Observing quantum correlations
   - Applications: quantum teleportation, QKD, quantum sensing

6. **Question 6: Quantum Phase Kickback** (`Question 6 - Quantum Phase Kickback.ipynb`)
   - Understanding phase kickback mechanism
   - Implementing the Deutsch algorithm
   - Controlled operations on eigenstates
   - Foundation of quantum algorithmic advantage

## Prerequisites

- Python 3.7+
- Qiskit
- Jupyter Notebook
- Matplotlib

## Installation

```bash
pip install -r requirements.txt
```

## Usage

Launch Jupyter Notebook and open any question file:

```bash
jupyter notebook
```

Navigate to the desired question notebook and run the cells sequentially.

## Quantum Computing Concepts Covered

### Basic Concepts
- **Quantum Gates**: Hadamard (H), Pauli-X, Pauli-Z, CNOT
- **Quantum Circuits**: Building and visualizing quantum circuits
- **Measurements**: Measuring qubits and analyzing results
- **OpenQASM**: Quantum assembly language
- **Circuit Properties**: Depth, width, and gate count
- **Quantum Simulators**: Using Qiskit Aer for simulations

### Intermediate Concepts
- **Quantum Superposition**: Creating and manipulating superposition states
- **Quantum Entanglement**: Bell states and multi-qubit correlations
- **Controlled Operations**: Two-qubit gates and conditional operations

### Advanced Concepts
- **Phase Kickback**: Extracting information through quantum phase
- **Quantum Algorithms**: Deutsch algorithm and quantum advantage
- **Eigenstate Operations**: Working with eigenstates and eigenvalues
- **Quantum Interference**: Constructive and destructive interference

## Learning Path

### Beginner Track
1. Start with basic gate operations (Question 1-2)
2. Understand the Qiskit environment (Question 3)
3. Explore quantum superposition and measurement (Question 4)

### Advanced Track
4. Master quantum entanglement and Bell states (Question 5)
5. Understand phase kickback and quantum algorithms (Question 6)

### Next Steps
- Implement Grover's search algorithm
- Study quantum error correction
- Explore variational quantum algorithms (VQE, QAOA)
- Run circuits on real IBM quantum hardware

## Resources

- [Qiskit Documentation](https://qiskit.org/documentation/)
- [IBM Quantum Experience](https://quantum-computing.ibm.com/)
- [Qiskit Textbook](https://qiskit.org/textbook/)

## Author

Jakob Richert

## License

This project is licensed under the MIT License - see the LICENSE file for details.
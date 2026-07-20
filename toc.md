# Quantum Computing: Zero to Hero
## Table of Contents - Working Draft v0.2
### Book URL: https://www.aialchemyhub.in/books/qalchemy/

**Audience**: STEM undergrads, software engineers, curious professionals. Assumes high-school math + basic Python.  
**Goal**: From "what's a qubit" to "I understand Grover's + why QML matters"  
**Format**: Each chapter = 1 lecture = 1 .md file = future `qalchemy` lab  
**Philosophy**: Theory first, code later. Every chapter standalone, but builds narrative.

---

### **Front Matter**
FM1. `front-matter/foreword.md` - Foreword by [Guest Expert Name] [Optional for v1.0]
FM2. `front-matter/from-author.md` - From the Author: Why I Wrote Quantum Computing: Zero to Hero
FM3. `front-matter/preface.md` - Preface: Scope, Audience, Prerequisites, How to Navigate
FM4. `front-matter/how-to-use.md` - Conventions: Math, Code, Diagrams, Exercises

### **Part 0: Foundations - Why Should You Care**
1. `ch01_classical_vs_quantum.md` - Bits vs Qubits, Reversible computing, Where QC wins
2. `ch02_math_primer.md` - Complex numbers, Linear algebra, Bra-Ket notation crash course
 
### **Part I: The Core Concepts - Building Blocks**
4. `ch03_qubit.md` - Bloch sphere, Superposition, Measurement collapse
5. `ch04_multi_qubit.md` - Tensor products, Entanglement, Bell states, No-cloning
6. `ch05_quantum_gates.md` - Pauli, Hadamard, CNOT, Universal gate sets
7. `ch06_quantum_circuits.md` - Circuit model, Depth, Width, Your first circuit

### **Part II: The Killer Algorithms - Where Quantum Wins**
8. `ch07_deutsch_jozsa.md` - Your first quantum speedup, Oracle concept
9. `ch08_grovers_algorithm.md` - Searching unsorted DB, Amplitude amplification
10. `ch09_shors_algorithm.md` - Factoring, Period finding, RSA implications
11. `ch10_quantum_fourier_transform.md` - The engine inside Shor's

### **Part III: The Reality Check - NISQ Era**
12. `ch11_noise_decoherence.md` - T1, T2, Why qubits are fragile
13. `ch12_error_correction.md` - Shor code, Surface code intuition
14. `ch13_variational_algorithms.md` - VQE, QAOA - Hybrid quantum-classical [Bridge to QML]

### **Part IV: Quantum Machine Learning - ABC of the Future**
15. `ch14_qml_landscape.md` - Why QML? Classical ML vs Quantum ML, Hype vs Reality
16. `ch15_data_encoding.md` - Amplitude, Angle, Basis encoding. How to put data in qubits
17. `ch16_quantum_kernels.md` - QSVM, Feature maps, Kernel trick with quantum advantage
18. `ch17_variational_circuits.md` - PQC as ML models, Training via parameter-shift
19. `ch18_qml_applications.md` - Chemistry VQE, Finance QAOA, Classification demos

### **Part V: Hands-On - From Theory to Code**
20. `ch19_qiskit_cirq_intro.md` - Setting up simulators, Hello quantum world
21. `ch20_build_deutsch_circuit.md` - Code walkthrough, Run on simulator
22. `ch21_build_grover_circuit.md` - 3-qubit Grover, Interpret results
23. `ch22_build_qml_classifier.md` - Code: QSVM on Iris dataset using Qiskit/PennyLane
24. `ch23_qalchemy_lab_setup.md` - Teaser: `pip install qalchemy-lab` workflow

### **Part VI: The Future**
25. `ch24_quantum_advantage.md` - What problems are actually quantum-suitable
26. `ch25_quantum_careers.md` - Research, Industry, Startups, How to contribute to qalchemy
27. `ch26_beyond_gate_model.md` - Annealing, Photonic, Topological - quick tour

### **Appendices**
A. `apdx_a_cheat_sheet.md` - Gate matrix reference, Common identities  
B. `apdx_b_python_refresher.md` - NumPy, Matplotlib for QC plots  
C. `apdx_c_qml_libraries.md` - PennyLane, TensorFlow Quantum, Qiskit Machine Learning  
D. `apdx_d_further_reading.md` - Nielsen & Chuang, Schuld & Petruccione, Papers  
E. `apdx_e_glossary.md` - All terms defined  

---


# Analysis of 6-Qubit QFT and Inverse QFT Topologies

This directory contains the computational simulation and mathematical verification of a 6-qubit Quantum Fourier Transform (QFT) and its exact inverse circuit (IQFT).

## Core Work Described in the Report

* **Probability Distribution Proofs:** Mathematical derivation demonstrating that the output probability for each computational basis state evaluates to exactly 50% ($P_{\text{ON}} = P_{\text{OFF}} = 50\%$) due to the balanced superposition profiles:
  $$\frac{1}{\sqrt{2}}(|0\rangle + e^{2\pi i \beta}|1\rangle)$$
* **IQFT Circuit Synthesis:** Structural implementation of the Inverse QFT using both black-box unitary definitions ($IQFT = QFT^{\dagger}$) and fully expanded quantum gate topologies (including inverse Hadamard, $S^{-1}$, $T^{-1}$, and controlled rotation components)[cite: 25].
* **Statevector Verification:** Numerical and visual confirmation of circuit fidelity by evaluating state transitions under specific input vectors, including $|0011\rangle$, $|1100\rangle$, and $|0101\rangle$, achieving 100% reconstruction accuracy at the output stage[cite: 25].

*Note: The primary analytical report is provided in Persian as institutional coursework verification, while the circuit schematics, matrix transformations, and mathematical proofs follow universal notation[cite: 25].*

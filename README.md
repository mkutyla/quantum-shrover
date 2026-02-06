# Quantum Shrover

## About

Quantum Shrover is a benchmarking and implementation suite for Shor's and Grover's algorithms for different quantum hardware. It evaluates them in terms of:
- Success probability.
- Circuit depth & complexity: analyzing how different transpilation strategies for various hardware backends impact the total number of gates.
- Hardware fidelity: comparing the performance of superconducting qubits versus trapped ions using the same algorithmic baseline.
- Error resilience: evaluating how effectively the algorithms scale as the number of qubits and circuit layers increases on real-world noisy devices (NISQ).

## Tested hardware

| Provider  | Chip / HW Name | Backend architecture | Qubits | Notes |
| :---      | :---           | :---                 | :---   | :---   |
| **IBM**   |    | superconducting   |   |   | 
| **AQT**   |    | trapped-ion       |   |   |
| **IQM**   |    | superconducting   |   |   |
| **ORCA**  |    | photonic          |   |   |

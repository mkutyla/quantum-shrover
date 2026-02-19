# Quantum Shrover

## About

Quantum Shrover is a benchmarking and implementation suite for Shor's and Grover's algorithms for different quantum hardware. It evaluates them in terms of:

- success probability.
- circuit depth & complexity: analyzing how different transpilation strategies for various hardware backends impact the total number of gates.
- hardware fidelity: comparing the performance of superconducting qubits versus trapped ions using the same algorithmic baseline.
- error resilience: evaluating how effectively the algorithms scale as the number of qubits and circuit layers increases on real-world noisy devices (NISQ).

## Tested hardware

| Provider  | Chip / HW name | Backend architecture | Qubits | Notes | Reference |
| :---      | :---           | :---                 | :---   | :---   | :--- |
| **IBM**   | Heron r3  | superconducting   |  156 |   |  |
| **IBM**   | Heron r2  | superconducting   |  156 |   |  |
| **IBM**   | Heron r1  | superconducting   |  133 |   |  |
| **IBM**   | Eagle r3  | superconducting   |  127 |   |  |
| **IQM**   | IQM Emerald   | superconducting   | 54 | transmon qubits, arranged in a square lattice  | [Docs](https://www.iqmacademy.com/qpu/emerald/) |
| **IQM**   | IQM Garnet    | superconducting   | 20 | transmon qubits, arranged in a square lattice  | [Docs](https://www.iqmacademy.com/qpu/garnet/) |
| **IQM**   | IQM Sirius    | superconducting   | 16 | transmon qubits, arranged in a star lattice   | [Docs](https://www.iqmacademy.com/qpu/sirius/) |
| **AQT**   | PIAST-Q       | trapped-ion       | 20  | all-to-all qubit connectivity |  |
| **ORCA**  |  PT-1             | photonic          |   |   |


---
The code in this repository is part of my Master's thesis @ PUT.
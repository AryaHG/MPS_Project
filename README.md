# MPS Project

Tensor network tools for turning arbitrary state vectors into Matrix Product States (MPS), plus small ensembles (Haar, Clifford, Fermionic Gaussian) for comparing entanglement via bond dimensions and Rényi/SRE metrics.

---

## At a glance

* **Author**: Arya Haghighian
* **Advisor**: Prof. James Whitfield (Dartmouth College)
* **Research group**: Quantum Computation + Quantum Information, Whitfield Group, Dartmouth College
* **Sponsors / acknowledgments**: Dartmouth College
* **Repo status**:  In progress

---

## What this project does

1. **Convert an arbitrary (2^N)-length state vector into an MPS** using sequential SVD (Schmidt) with a cutoff to control bond growth.
2. **Reconstruct the state from the MPS** (sanity check via tensor contractions).
3. **Generate comparison ensembles**:

   * Haar‑random states (QR of random complex matrix)
   * Clifford‑random states (stabilizer circuits)
   * Fermionic Gaussian states (Slater determinants / quadratic Hamiltonians)
4. **Measure entanglement** at the mid‑bond via singular values / bond dimension; compute Rényi entropies; discuss SRE vs. Haar.

---

## Quickstart

### 1) Clone and enter

```bash
git clone https://github.com/AryaHG/MPS_Project.git
cd MPS_Project
```

### 2) Environments

This repo currently uses Jupyter notebooks. Two stacks appear across notebooks:

* **Julia (recommended)**

  * `julia` ≥ 1.10
  * Packages: `LinearAlgebra`, `TensorOperations`, `Random`, (optional plotting)
  * Optional: `ITensors` if you plan to extend to MPOs

* **Python (for Clifford demos/Qiskit)**

  * Python ≥ 3.10
  * `qiskit`

You can launch with:

```bash
jupyter lab
```

Then open the notebooks in `notebooks/`.

> Tip: if you use VS Code, install the Julia and Python extensions and open the folder as a workspace.


## Sponsors: 


---
## How to cite


---

## License


---

## Acknowledgments

James D. Whitfield
Whitfield Group


---


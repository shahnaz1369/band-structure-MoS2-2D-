# Electronic Band Structure of Monolayer MoS₂ Using the Tight-Binding Method

## Overview

This repository provides a Python implementation for calculating and visualizing the electronic band structure of monolayer molybdenum disulfide (MoS₂) using the Slater–Koster Tight-Binding (TB) formalism. The implementation is developed in Jupyter Notebook and demonstrates the construction of the Tight-Binding Hamiltonian together with the numerical calculation of the energy dispersion along the high-symmetry path of the first Brillouin zone.

Monolayer MoS₂ is a representative transition metal dichalcogenide (TMD) with remarkable electronic and optical properties, including a direct band gap, strong spin–orbit coupling, and excellent potential for applications in nanoelectronics, optoelectronics, valleytronics, and photonics.

---

## Physical Model

The electronic structure is described using an eleven-orbital Slater–Koster Tight-Binding model.

Each primitive unit cell contains:

* One Molybdenum (Mo) atom
* Two Sulfur (S) atoms

The Hamiltonian is constructed by considering:

* Mo d-orbitals
* S p-orbitals
* Nearest-neighbor hopping interactions
* Slater–Koster overlap parameters

The eigenvalue problem is solved for each k-point along the high-symmetry path (Γ–K–M–Γ) to obtain the electronic band structure.

---

## Features

* Python implementation of the Slater–Koster Tight-Binding model for monolayer MoS₂
* Construction of the Hamiltonian matrix using orbital interactions
* Implementation of Slater–Koster hopping parameters
* Numerical diagonalization of the Hamiltonian
* Calculation of electronic energy bands
* Band structure visualization using Matplotlib
* Well-documented Jupyter Notebook suitable for educational and research purposes

---

## Slater–Koster Parameters

The implementation includes the following hopping integrals:

* (V_{pp\pi})
* (V_{pp\sigma})
* (V_{pd\sigma})
* (V_{pd\pi})
* (V_{dd\sigma})
* (V_{dd\pi})
* (V_{dd\delta})

These parameters are used to construct the interaction matrices between Mo and S orbitals.

---

## Repository Structure

```text
band-structure-MoS2-2D
│
├── MoS2.ipynb          # Main notebook
├── README.md           # Project documentation
├── requirements.txt    # Python dependencies
├── figures/            # Generated figures
└── LICENSE
```

---

## Requirements

The notebook requires the following Python packages:

* numpy
* matplotlib

Install the required packages using:

```bash
pip install -r requirements.txt
```

---

## How to Run

1. Clone the repository.

```bash
git clone https://github.com/your_username/band-structure-MoS2-2D.git
```

2. Navigate to the project directory.

```bash
cd band-structure-MoS2-2D
```

3. Launch Jupyter Notebook.

```bash
jupyter notebook
```

4. Open **MoS2.ipynb** and execute the notebook cells sequentially.

---

## Results

The notebook calculates the eigenvalues of the Tight-Binding Hamiltonian and plots the electronic band structure of monolayer MoS₂ along the high-symmetry path of the first Brillouin zone.

A typical output is shown below.

<img width="846" height="584" alt="image" src="https://github.com/user-attachments/assets/e1f07d65-3d82-43b4-a1aa-d55a4e51c19a" />


---

## Applications

This project can be used for:

* Tight-Binding model development
* Electronic structure calculations
* Two-dimensional materials research
* Condensed matter physics education
* Photonics and optoelectronic device studies
* Validation of DFT and Quantum ESPRESSO calculations

---

## References

1. Liu, G.-B., Shan, W.-Y., Yao, Y., Yao, W., & Xiao, D. *Three-band tight-binding model for monolayers of group-VIB transition metal dichalcogenides.*

2. Cappelluti, E., Roldán, R., Silva-Guillén, J. Á., Ordejón, P., & Guinea, F. *Tight-binding model and direct-gap/indirect-gap transition in single-layer and multilayer MoS₂.*

3. Ridolfi, E., et al. *A tight-binding model for MoS₂ monolayers.*

---

## Future Improvements

Potential extensions of this project include:

* Spin–Orbit Coupling (SOC)
* Density of States (DOS)
* Projected Density of States (PDOS)
* Effective mass calculation
* Berry curvature
* Valley polarization
* Comparison with Density Functional Theory (DFT)
* Extension to other transition metal dichalcogenides (WS₂, MoSe₂, WSe₂)

---

## License

This project is released under the MIT License.

---

## Author

**Shahnaz Mohammadi**

<img width="846" height="584" alt="image" src="https://github.com/user-attachments/assets/d1b67a45-2e7c-4e23-aeb3-91242a6e4a6f" />


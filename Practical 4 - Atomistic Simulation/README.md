# Practical 4 — Atomistic Simulation

**Supervisor:** Zhipeng Yao · **Tools:** [ASE](https://wiki.fysik.dtu.dk/ase/), [ASAP3](https://wiki.fysik.dtu.dk/asap/) (EMT, Brenner potential)

Get to know a complex existing code (ASE), compute 0 K material properties by molecular
statics, and simulate bond breaking of a carbon nanotube with molecular dynamics.

## Tasks

- **2 · Potentials** — literature research: EMT vs. other (semi-)empirical potentials
- **3 · Molecular statics**
  - sc / bcc / fcc structures and their minimum energies at 0 K
  - elastic constants C₁₁, C₁₂, C₄₄ of fcc Cu from strain–energy relations
  - validity of the quadratic energy–strain assumption
- **4 · Molecular dynamics of CNTs**
  - CNT types and chirality
  - critical deformation rate; energy increase under deformation
  - NVT uniaxial tension test
  - bond-breaking energy with the Brenner potential

## Solution

- `report/main.tex`, `report/Ghelichkhani_MatSim_Practical4_Atomistic.pdf` — Part I: literature research on the potentials (Task 2.1),
  the strain states for the elastic constants (Tasks 3.1, 3.3, 3.4) and the discussion of all results
- `atomistic.ipynb` — Part II: molecular statics of Cu and molecular dynamics of a (5,5) nanotube
  (Tasks 3.2, 3.5, 3.6, 4.1–4.5)

## Material (local only)

- `Practical 4 - Atomistic.pdf` — tutorial script

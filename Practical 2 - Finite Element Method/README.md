# Practical 2 — Solid Mechanics & Linear Finite Element Analysis

**Supervisor:** Yuxin Luo · **Tools:** Python (NumPy/Matplotlib) or MATLAB

Derive the governing PDE of linear elasticity from Newton's 2nd law and write a 1D linear
finite element code for an elastic, clamped bar with variable cross-section under tension.

## Tasks

- **1 · Balance laws** — local form of momentum balance, static case
- **2 · Linear elasticity** — Hooke's law in index notation; 21 independent stiffness
  components; 1D bar boundary value problem
- **3 · Weak form** of the bar problem
- **4 · Shape functions** — linear elements
- **5 · Element level** — numerical integration (trapezoidal / Newton–Cotes), element stiffness
- **6 · Assembly** of the global system
- **7 · Dirichlet BCs** — permutation / partitioning of the global system
- **8 · Full analysis** — 1D FE run and post-processing

## Solution

- `report/main.tex`, `report/main.pdf` — Part I: theory and hand calculations (Tasks 1.1–3.1,
  5.2, 5.3, 6.1, 6.3, 7.1)
- `fem1d.ipynb` — Part II: the 1D finite element code (Tasks 4.1, 4.2, 5.1–5.3, 6.2, 6.3, 7.2, 8.1)

## Material (local only)

- `Practical 2 - FEM.pdf` — tutorial script

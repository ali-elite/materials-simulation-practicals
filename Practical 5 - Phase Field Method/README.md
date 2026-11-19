# Practical 5 — Phase-Field Method

**Supervisor:** Frank Wendler · **Tools:** Python, [FiPy](https://www.ctcms.nist.gov/fipy/)

Revisit the phase-field formalism — order parameters, free-energy functional, kinetics — and
its finite-volume discretization, then apply it to solidification and Ni–Al γ/γ′ energetics.

## Tasks

- **Theory** — microstructure description, thermodynamics, kinetics; finite volume method
  (discretization, boundary conditions, explicit vs. implicit)
- **1 · 1D single-component solidification** (own code and/or FiPy)
- **2 · Bulk energy density coefficient** — Ni–Al, γ and γ′ phases
- **3 · Gradient energy density coefficient**

## Solution

- `report/main.tex`, `report/Ghelichkhani_MatSim_Practical5_PhaseField.pdf` — Part I: phase-field theory, finite volume method, analytic
  equilibrium interface and discussion of Tasks 1–3
- `phasefield.ipynb` — Part II: 1D Allen–Cahn solidification (FiPy), Ni–Al `f0`, Cahn–Hilliard
  interface energy vs `Kc`, 2D spinodal decomposition

## Material (local only)

- `Practical05_PhaseField_Method.pdf` — tutorial script
- `literature/` — Guyer et al. 2009 (FiPy), LeSar ch. 12 & App. C, functional derivative notes

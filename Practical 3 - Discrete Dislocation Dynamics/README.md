# Practical 3 — Discrete Dislocation Dynamics

**Supervisor:** Leon Pyka · **Tools:** [microMegas](https://github.com/LAPikachu/practical_DDD) (mM) + Python wrapper

Model plasticity at the mesoscale, where dislocations dominate the mechanical response, and
study the activation of a Frank–Read source in an FCC copper single crystal.

## Tasks

- **1 · Setup** — build mM, configure a Cu single crystal and a Frank–Read source via the
  `SimulationConfig` wrapper; estimate and then determine the critical shear stress; fit α
- **2 · Segment length** — critical shear stress vs. initial segment length (50–200 nm)
- **3 · Line orientation** — critical shear stress vs. character angle β (edge → screw)

## Solution

- `report/main.tex`, `report/main.pdf` — Part I: DDD and Frank–Read theory, discussion of Tasks 1–3
- `ddd_frank_read.ipynb` — Part II: microMegas runs (critical stress by bisection, length and
  orientation studies, parameter sensitivity)

To re-run the notebook, clone the course repository into `practical_DDD/` (git-ignored), delete the
shipped Linux objects in `dd/bin/mm.objs/` and build with `make mm` in `dd/bin`.

## Material (local only)

- `Practical 3 - DDD.pdf` — tutorial script

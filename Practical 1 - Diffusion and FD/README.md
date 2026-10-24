# Practical 1 — Diffusion & Finite Differences

**Supervisor:** Xingchen Tan · **Tools:** Python (NumPy/SciPy/Matplotlib) or MATLAB

Derive the governing equations for diffusion from Fick's laws, discretize the stationary case
with finite differences, and verify the numerical solution against physical expectations.

## Tasks

- [ ] **1 · Theory** — Fick's 2nd law in 2D for anisotropic diffusion; classify the PDE;
  reduce stationary diffusion to the Laplace equation by a change of variables
- [ ] **2 · Discretization** — 2nd-order central difference scheme on an equidistant mesh
- [ ] **3 · Boundary conditions** — Dirichlet and Neumann
- [ ] **4 · Linear system** — assemble it; analyse matrix structure and properties
- [ ] **5 · Implementation** — solver for an `lx × ly` rectangle; test problems and verification

## Material (local only)

- `Practical 1 - Diffusion and FD.pdf` — tutorial script

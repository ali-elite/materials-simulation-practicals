# Materials Simulation Practicals

Solutions to the **Practicals Materials Simulation**, part of the *Foundations of Materials
Simulation* module at the [Institute of Materials Simulation (WW8)](https://www.matsim.techfak.fau.de/),
Friedrich-Alexander-Universität Erlangen-Nürnberg, winter semester 2026/27.

Each practical follows a tutorial script: derive the governing equations, implement or apply
a numerical method, then verify and interpret the results. Each practical is submitted as a
report (~7–15 pages) together with the simulation code and approved by the supervisor.

## Contents

1. [Diffusion and Finite Differences](Practical%201%20-%20Diffusion%20and%20FD/) —
   Fick's laws, central-difference discretization of stationary diffusion, Dirichlet and
   Neumann boundary conditions.
2. [Finite Element Method](Practical%202%20-%20Finite%20Element%20Method/) —
   linear elasticity, weak form and a 1D finite element code for a clamped bar under tension.
3. [Discrete Dislocation Dynamics](Practical%203%20-%20Discrete%20Dislocation%20Dynamics/) —
   activation of a Frank–Read source in copper with microMegas.
4. [Atomistic Simulation](Practical%204%20-%20Atomistic%20Simulation/) —
   molecular statics of Cu (lattice and elastic constants) and molecular dynamics of carbon
   nanotubes with ASE.
5. [Phase Field Method](Practical%205%20-%20Phase%20Field%20Method/) —
   free-energy functional, Allen–Cahn kinetics and 1D solidification with FiPy.
6. [Kinetic Monte Carlo](Practical%206%20-%20Kinetic%20Monte%20Carlo/) —
   thermally activated diffusion, coarse graining and Au diffusion in Si via the kick-out
   mechanism.

Each folder contains its own README with objectives, tasks and tools.

## Requirements

Python 3.10 or newer. Install the dependencies with:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Notes:

- The DDD practical uses microMegas, built from the
  [course repository](https://github.com/LAPikachu/practical_DDD).
- If `pip install asap3` fails on macOS, use `conda install -c conda-forge asap3`.

## Course material

The tutorial scripts and literature are not included in this repository, as they are
copyrighted by their respective authors and publishers. They are available on StudOn or
from the supervisors. PDFs are git-ignored, except those in a `report/` folder.

## License

The code in this repository is released under the [MIT License](LICENSE).

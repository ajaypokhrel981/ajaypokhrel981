# Hi, I'm Ajay Pokhrel

### Computational fluid dynamics · Fluid flow · Heat transfer

I work on CFD coursework and simulation projects using **OpenFOAM** and **ANSYS Fluent**, with **Python** and **ParaView** for post-processing. This portfolio brings together simulation setups, technical reports, visual results, and notes on reproducibility.

## Featured projects

### [OpenFOAM T-junction flow](https://github.com/ajaypokhrel981/openfoam-t-junction-flow)

Steady, incompressible turbulent flow through a three-dimensional pipe junction with one inlet and two outlets.

- **Workflow:** STL geometry, `blockMesh`, `snappyHexMesh`, `simpleFoam`, and k–ω SST turbulence modelling.
- **Evidence:** a rebuilt 183,378-cell mesh passed `checkMesh`, and the OpenFOAM v2412 workflow completed 500 solver iterations.
- **Explore:** [case files](https://github.com/ajaypokhrel981/openfoam-t-junction-flow/tree/main/case) · [verification logs](https://github.com/ajaypokhrel981/openfoam-t-junction-flow/tree/main/results/verification) · [technical report](https://github.com/ajaypokhrel981/openfoam-t-junction-flow/blob/main/docs/assessment-report.pdf)

*Successful execution is documented; convergence, physical accuracy, and mesh independence still require assessment.*

### [Conjugate heat transfer — ANSYS Fluent](https://github.com/ajaypokhrel981/ansys-fluent-conjugate-heat-transfer)

A coursework reproduction study of forced convective cooling around a conducting square obstacle in a channel, based on Young & Vafai (1998).

- **Workflow:** Fluent case files, a parabolic inlet velocity UDF, Nusselt-number exports, and Python contour post-processing.
- **Materials:** native simulation archives, geometry, temperature and streamline figures, and original reports.
- **Explore:** [results](https://github.com/ajaypokhrel981/ansys-fluent-conjugate-heat-transfer/tree/main/results/figures) · [post-processing](https://github.com/ajaypokhrel981/ansys-fluent-conjugate-heat-transfer/tree/main/postprocessing) · [verification notes](https://github.com/ajaypokhrel981/ansys-fluent-conjugate-heat-transfer/blob/main/docs/verification-notes.md)

*This is a preserved simulation archive. Documented differences between saved settings and report descriptions remain to be resolved before claiming benchmark validation.*

## Tools used in these projects

| Area | Tools and methods |
| --- | --- |
| CFD | OpenFOAM, ANSYS Fluent, RANS, conjugate heat transfer |
| Meshing and setup | blockMesh, snappyHexMesh, STL geometry, boundary conditions |
| Post-processing | ParaView, Python, NumPy, pandas, SciPy, Matplotlib |
| Technical communication | Simulation reports, result figures, verification records |

## How I present simulation work

I keep original results distinguishable from rerun evidence, document the setup and execution steps, and state verification limits alongside numerical claims. Each project README is the starting point for its methods, results, and remaining checks.

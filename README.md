<div align="center">

# Ajay Pokhrel
### Mechanical Engineer · Computational Fluid Dynamics · Heat Transfer

ANSYS Fluent &nbsp; | &nbsp; OpenFOAM &nbsp; | &nbsp; Python &nbsp; | &nbsp; ParaView

**Exploring fluid flow and thermal systems through simulation, visualisation, and documented engineering work.**

[Fluent project](https://github.com/ajaypokhrel981/ansys-fluent-conjugate-heat-transfer) · [OpenFOAM project](https://github.com/ajaypokhrel981/openfoam-t-junction-flow)

</div>

---

## About me

I'm a mechanical engineering graduate from **Tribhuvan University, Nepal**, and a **Mechanical Engineering Instructor at Lahan Technical School**. My interests centre on computational heat transfer, internal flows, and thermal management.

- **Project experience:** conjugate heat transfer in ANSYS Fluent and turbulent pipe-junction flow in OpenFOAM.
- **Undergraduate thesis:** numerical modelling of a closed-loop pulsating heat pipe in ANSYS Fluent using VOF and Lee phase-change modelling.
- **Currently developing:** OpenFOAM proficiency, scientific Python, and simulation verification and validation.
- **Research direction:** CFD and heat transfer for thermal-management applications.

This portfolio brings together simulation setups, technical reports, visual results, and reproducibility notes. My OpenFOAM and Python skills are developing through coursework and practical projects.

## Featured simulation projects

### 01 · Conjugate heat transfer — ANSYS Fluent

**Forced convective cooling of a conducting square obstacle in a channel**, based on Young & Vafai (1998).

[![Original Re1000 temperature contours from the coursework archive](https://raw.githubusercontent.com/ajaypokhrel981/ansys-fluent-conjugate-heat-transfer/main/results/figures/Re1000/Re1000_paperstyle_isotherms.png)](https://github.com/ajaypokhrel981/ansys-fluent-conjugate-heat-transfer)

| Focus | Project evidence |
| --- | --- |
| Setup | Fluent case files, geometry, and a parabolic inlet velocity UDF |
| Post-processing | Nusselt-number exports and Python contour plotting |
| Documentation | Original reports, archived results, and verification notes |

**Status:** preserved coursework simulation archive. Differences between saved-case settings and report descriptions remain unresolved; benchmark validation has not been established by the repository review.

[Explore repository →](https://github.com/ajaypokhrel981/ansys-fluent-conjugate-heat-transfer) · [Results](https://github.com/ajaypokhrel981/ansys-fluent-conjugate-heat-transfer/tree/main/results/figures) · [Post-processing](https://github.com/ajaypokhrel981/ansys-fluent-conjugate-heat-transfer/tree/main/postprocessing) · [Verification notes](https://github.com/ajaypokhrel981/ansys-fluent-conjugate-heat-transfer/blob/main/docs/verification-notes.md)

### 02 · T-junction flow — OpenFOAM

**Steady, incompressible turbulent flow through a three-dimensional pipe junction** with one inlet and two outlets.

[![Original T-junction velocity contour from the coursework run](https://raw.githubusercontent.com/ajaypokhrel981/openfoam-t-junction-flow/main/results/original/velocity-contour.png)](https://github.com/ajaypokhrel981/openfoam-t-junction-flow)

| Focus | Project evidence |
| --- | --- |
| Meshing | STL geometry, `blockMesh`, and `snappyHexMesh` |
| Solution | `simpleFoam` with k–ω SST turbulence modelling |
| Execution checks | Rebuilt 183,378-cell mesh passed `checkMesh`; 500 solver iterations completed in OpenFOAM v2412 |

**Status:** workflow execution verified. Convergence, physical accuracy, and mesh independence still require assessment. The image above shows original coursework results, not the verification rerun.

[Explore repository →](https://github.com/ajaypokhrel981/openfoam-t-junction-flow) · [Case files](https://github.com/ajaypokhrel981/openfoam-t-junction-flow/tree/main/case) · [Verification logs](https://github.com/ajaypokhrel981/openfoam-t-junction-flow/tree/main/results/verification) · [Technical report](https://github.com/ajaypokhrel981/openfoam-t-junction-flow/blob/main/docs/assessment-report.pdf)

## Tools used in these projects

| Area | Tools and methods |
| --- | --- |
| CFD | ANSYS Fluent, OpenFOAM, RANS, conjugate heat transfer |
| Meshing and setup | `blockMesh`, `snappyHexMesh`, STL geometry, boundary conditions |
| Post-processing | ParaView, Python, NumPy, pandas, SciPy, Matplotlib |
| Technical communication | Simulation reports, result figures, verification records |

## How I document engineering work

I describe the physical problem, numerical setup, and execution steps; retain original results separately from rerun evidence; and state verification limits alongside numerical claims. Each project README explains the methods, available results, and remaining checks.

---

<div align="center">

**CFD · Heat transfer · Thermal management**  
Based in Nepal

</div>

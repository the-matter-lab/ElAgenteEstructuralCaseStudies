# DFT Validation of H₂O-Bound Co–Pc Structures

This directory contains the DFT geometry optimization and vibrational frequency calculation results for five H₂O-bound Co–Pc structures generated in the tool-ablation test (Figure S22c). The corresponding validation results are presented in Figure S23.

All calculations were performed at the B3LYP-D4/def2-SVP level of theory, with a total charge of 0 and a spin multiplicity of 2.

Each `run` directory contains the following files, where `N` denotes the run number (1–5):

| File | Description |
| --- | --- |
| `runN.out` | ORCA output containing the calculation input, geometry optimization results, and vibrational frequencies. |
| `runN.xyz` | Final DFT-optimized geometry. |
| `runN_trj.xyz` | Geometry optimization trajectory, including the initial structure, intermediate steps, and final structure. |
| `runN.hess.v006.xyz` | XYZ trajectory illustrating the imaginary vibrational mode, provided only for Runs 1 and 5. |

Imaginary frequencies were identified only for Runs 1 and 5. Separate ORCA input (`.inp`) and Hessian (`.hess`) files are not provided.

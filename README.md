# Scale Formation from Dissolved Organic Matter in SAGD Steam Generators — Part II

Data and code supplementary to:

**Scale Formation from Dissolved Organic Matter in SAGD Steam Generators — Part II: Alkaline, Neutral, and Sulfur-rich Species Characterized by ESI-P and APPI-P FTICR-MS**
Ali Naderi and Thomas B. P. Oldenburg

*DOI: to be added upon publication.*
Companion to Part I: [https://doi.org/10.1021/acs.energyfuels.5c01778](https://doi.org/10.1021/acs.energyfuels.5c01778)

## Overview

This repository provides the raw FTICR-MS data and the statistical analysis code for Part II of this study. Part II characterizes alkaline, neutral, and sulfur-rich species using FTICR-MS in positive electrospray ionization (ESI-P) and positive atmospheric pressure photoionization (APPI-P) modes, extending the ESI-N (acidic species) work reported in Part I.

Six boiler feed water (BFW) samples from Athabasca (SAGD) and Cold Lake (CSS) facilities in Alberta, Canada, were heated to 300 °C in a closed reactor. The fluids and the thermally generated solids were analyzed to evaluate compositional changes associated with organic scale formation in once-through steam generators (OTSGs). Samples were collected during 2020 and 2021 and analyzed from 2020 to 2024.

## Data files

| File | Ionization mode | Contents |
| --- | --- | --- |
| `BFWs_ESIP-FTICR-MS.xlsx` | ESI-P (positive electrospray) | Identified chemical formulas for BFWs, heated BFWs, and generated solids |
| `BFWs_APPIP-FTICR-MS.xlsx` | APPI-P (positive atmospheric pressure photoionization) | Identified chemical formulas for BFWs, heated BFWs, and generated solids |

### Sheet naming convention

Each sheet name serves as an ID for a sample. The naming follows the same convention as Part I:

- A sheet named with the BFW ID (e.g., `XX`) contains the unheated BFW.
- The corresponding heated BFW is the same ID plus `16` (e.g., `XX16`).
- Solids generated during heating are provided in their associated sheets.

Samples originate from Athabasca (SAGD) and Cold Lake (CSS) facilities.

## Code

Python scripts in this repository reproduce the statistical analyses reported in the paper:

- Principal Component Analysis (PCA)
- K-Means clustering
- Correlation analysis

These analyses cluster samples by geographical origin and sample type (BFW, heated BFW, solids) and identify compositional predictors of solid formation.

## Citation

If you use this data or code, please cite the paper (DOI above) and Part I ([https://doi.org/10.1021/acs.energyfuels.5c01778](https://doi.org/10.1021/acs.energyfuels.5c01778)).

## Contact

Ali Naderi — [github.com/Ali-Naderi-Gh](https://github.com/Ali-Naderi-Gh)

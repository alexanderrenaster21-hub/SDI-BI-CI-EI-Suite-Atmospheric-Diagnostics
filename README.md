# SDI-BI-CI-EI-Suite-Atmospheric-Diagnostics
Official repository for the foundational study: A Multi-Level Teleconnection &amp; Dynamic Coupling Diagnostic Framework via the SDI–BI–CI–EI Suite (1940–2026). Includes 1,041-month ERA5 master database, PDF table &amp; monograph. Author: Alexander Valentinus Renășteanu (Galway, Ireland). DOI: 10.5281/zenodo.23012661

# A Multi-Level Teleconnection and Dynamic Coupling Diagnostic Framework
### Decoupling Stratospheric Wave Geometry and Eurasian Blocking via the Standardized SDI–BI–CI–EI Suite (1940–2026)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23012661.svg)](https://doi.org/10.5281/zenodo.23012661)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0006--3854--8911-green.svg)](https://orcid.org/0009-0006-3854-8911)
[![Open Access](https://img.shields.io/badge/Open_Access-Enabled-blue.svg)](https://doi.org/10.5281/zenodo.23012661)

---

## Author & Institutional Affiliation
* **Author:** Alexander Valentinus Renășteanu
* **Role:** Citizen Scientist & Independent Researcher in Fluid Geodynamics and Dynamic Climatology
* **Location:** Galway, Ireland
* **ORCID:** [0009-0006-3854-8911](https://orcid.org/0009-0006-3854-8911)
* **Corresponding Email:** alexander.renaster21@gmail.com
* **Official Permanent DOI:** [10.5281/zenodo.23012661](https://doi.org/10.5281/zenodo.23012661) | OpenAIRE Indexed
* **Operational Diagnostic Freeze:** Thursday, September 17, 2026, 09:15 IST

---

## Abstract
Classical univariate teleconnection metrics frequently fail to capture the non-linear, vertical, and sub-seasonal coupling between middle-stratospheric momentum deposition and lower-tropospheric boundary conditions across the Euro-Mediterranean domain. This foundational study presents the comprehensive mathematical formulation, epistemological justification, and empirical physical validation of the **SDI–BI–CI–EI Suite**, an integrated multi-level diagnostic system standardized on a continuous, dimensionless metric spanning from minus four to plus four ($[-4.0, +4.0]$). 

The framework is verified across an uninterrupted historical matrix of 1,041 empirical monthly records derived from ECMWF ERA5 reanalyses and global observational archives between January 1, 1940, and September 15, 2026. The suite systematically decouples middle-stratospheric wave interference from near-surface continental advection by establishing four orthogonal diagnostic axes:
1. **Split-Displacement Index (SDI) at 10 hPa:** Discriminates between Planetary Wave-1 off-pole displacements and Planetary Wave-2 resonant bifurcations via discrete Fourier harmonic analysis, Eliassen-Palm eddy heat flux convergence, and spatial inertia ellipticity tensors.
2. **Buran Index (BI) at 850 hPa and Surface:** Evaluates the structural horizontal continuity of the Eurasian Voejkov Bridge ($\ge 1045\text{--}1048\text{ hPa}$), lower-tropospheric Siberian cold-core charging ($\Delta T_{850} \le -16\,^\circ\text{C}$), and adverse Mediterranean cyclonic aspiration ($P \le 995\text{ hPa}$).
3. **Christmas Index (CI):** Resolves sub-seasonal wave preconditioning, high-latitude blocking persistence, and coastal snow squalls across the late-December festive window (December 22–27).
4. **Easter Index (EI):** Integrates dynamic Final Stratospheric Warming timing with a non-linear astronomical insolation decay function ($\Phi_{\text{Astr}}$) derived from Gregorian Computus algorithms to diagnose late-season Arctic outbreaks.

By evaluating 86 years of reanalysis data, this work resolves fundamental dynamical paradoxes: explaining why extreme stratospheric warmings can trigger mild European zonal flows (the *Canadian Catch Paradox*), why historic continental freezes can emerge from off-pole displacements without circumpolar wind reversal (the *Independent Continental Advection Paradox*), and how sub-seasonal phenological metrics overcome the artificial smoothing of standard monthly averages.

---

## The Four Diagnostic Axes of the Suite

| Index | Target Layer | Primary Physical Mechanics | Standardized Domain |
| :--- | :---: | :--- | :---: |
| **SDI** *(Split-Displacement Index)* | $10\text{ hPa}$ Stratosphere | Fourier wave ratio ($R_2/R_1$), Eliassen-Palm flux, vortex ellipticity tensor, and QBO/ENSO vertical coupling. | $[-4.0, +4.0]$ |
| **BI** *(Buran Index)* | $850\text{ hPa}$ \& Surface | Voejkov Bridge continuity line-integral, Siberian cold pool charge, and Mediterranean cyclonic draw. | $[-4.0, +4.0]$ |
| **CI** *(Christmas Index)* | Fixed Festive Window (Dec 22–27) | Pre-festive stratospheric wave latency, Scandinavian blocking, Mediterranean lee cyclogenesis, and Adriatic Snow Effect (ASE). | $[-4.0, +4.0]$ |
| **EI** *(Easter Index)* | Mobile Vernal Window (Computus) | Final Stratospheric Warming dynamics, polar jet meander amplitude, and non-linear astronomical insolation correction ($\Phi_{\text{Astr}}$). | $[-4.0, +4.0]$ |

---

## Repository Contents & Data Governance

* `MASTER_DATABASE_ERA5_1940_2026_FINAL_34COL.csv`: Complete empirical climatological dataset comprising 1,041 monthly records and 34 standardized parameters extracted from ECMWF ERA5 reanalyses and NOAA archives (1940–2026).
* `Studio su SDI, BI, CI e EI ufficiale (1).pdf` : Official peer-reviewed/preprint monograph detailing the mathematical derivations, theoretical epistemology, and 86-year case study validations (1956, 1962/63, 1970, 1985, 1991/92, 1996, 2012, 2013, 2018, 2019).
* `Master_Database_ERA5_1940_2026_PDF_Table.pdf`: Full-table human-readable PDF export of the 1,041 empirical time steps.

---

## Master Matrix Parameter Architecture (34 Columns)

The dataset is structured across four thematic blocks:
1. **Temporal & Polar Vortex Kinematics (Cols 1–11):** Day, Month, Year, VPT Mode (N/D/S), NAM anomaly ($\sigma$), SDI ($10\text{ hPa}$), BI ($850\text{ hPa}$), CI, EI, Target Dates.
2. **Equatorial Pacific & ENSO Diversity (Cols 12–20):** Phase, Longitudinal Domain (EP vs CP), Intensity, Modoki Status, SSTA (Niño 1+2, Niño 3.4, Niño 4), Absolute Niño 3.4 SST in Celsius and Kelvin ($T(K) = T(^\circ C) + 273.15$).
3. **Equatorial Stratosphere & Multidecadal Basins (Cols 21–26):** QBO zonal wind ($20\text{--}30\text{ hPa}$), Wind Direction (W/E), QBO velocity anomaly, PDO index, AMO ($^\circ\text{C}$), IOD ($^\circ\text{C}$).
4. **Convection, Heliophysics, Geometry & External Radiative Forcings (Cols 27–34):** MJO Phase \& Amplitude, Sunspot Number (SSN), Solar Cycle Phase, Gauss lunisolar parameter, Vortex Ellipticity ($\mathcal{E}_{\text{VPS}}$), Secular Warming Drift, Volcanic Stratospheric Aerosol Optical Depth ($\tau_{\text{AOD}}$).

---

## Citation & Academic Indexing

### BibTeX
```bibtex
@misc{renasteanu2026framework,
  author       = {Ren{\u{a}}{\c{s}}teanu, Alexander Valentinus},
  title        = {{A Multi-Level Teleconnection and Dynamic Coupling Diagnostic 
                   Framework: Decoupling Stratospheric Wave Geometry and Eurasian 
                   Blocking via the SDI--BI--CI--EI Suite (1940--2026)}},
  month        = sep,
  year         = 2026,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.23012661},
  url          = {https://doi.org/10.5281/zenodo.23012661}
}

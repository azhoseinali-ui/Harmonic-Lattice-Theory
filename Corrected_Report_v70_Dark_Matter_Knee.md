# Corrected Report: Harmonic Lattice Theory and Dark Matter

**Version 70.0 – Attempted numerical consistency between the 12.68 TeV scale and the cosmic-ray knee**

**Author:** Engineer Hossein-Ali Azh  
**Date:** 22 August 2026  
**Status:** Internal correction note (not yet a peer-reviewed submission)

---

## Executive Summary

This document collects the latest numerical attempts within Harmonic Lattice Theory to relate the predicted dark-matter mass scale (~12.68 TeV) to the observed cosmic-ray knee (~4 PeV). Multiple intermediate factors (topological correction S, hierarchical clustering, two plasma-resonance orientations, and an additional galactic aggregation factor) are introduced. The author asserts that all factors derive from the same geometric set {C60, E8, FCC, α, K_geom}. Whether these factors are uniquely determined by the underlying lattice or function as adjustable multipliers remains an open question for independent verification.

---

## 1. Basic Geometric Parameters

| Parameter          | Value                  | Source / Remark                          |
|--------------------|------------------------|------------------------------------------|
| R_lat              | 2^18 = 262144          | Lattice node count                       |
| D                  | 80                     | Lattice tensor (240/3)                   |
| N_sol              | 60                     | C60 vertices                             |
| G_DM               | 0.25948                | FCC void fraction                        |
| K_geom             | 0.5346                 | Voronoi geometric coefficient            |
| α                  | 1/137.035999177        | Fine-structure constant                  |
| m_e                | 510998.950 eV          | Electron mass (experimental input)       |

---

## 2. Base Soliton Energy

$$
E_{\rm sol} = \frac{m_e}{N_{\rm sol}} = \frac{510998.950}{60} = 8516.649\,{\rm eV}
$$

---

## 3. Raw Dark-Matter Mass from Lattice

$$
M_{\rm DM}^{(\rm raw)} = \left(\frac{R_{\rm lat}}{D}\right)^2 \times G_{\rm DM} \times E_{\rm sol} \approx 23.73\,{\rm GeV}
$$

---

## 4. Topological Correction Factor

$$
S = \frac{1}{\alpha} \times \frac{1}{K_{\rm geom}} \times \frac{D}{R_{\rm lat}} \times N_{\rm sol} \approx 4.69
$$

$$
M_{\rm DM}^{(\rm intermediate)} = 23.73\,{\rm GeV} \times 4.69 \approx 111.3\,{\rm GeV}
$$

A further hierarchical scaling is required to reach the target 12.68 TeV. The precise origin of this additional factor is not uniquely fixed by the listed geometric parameters alone.

---

## 5. Hierarchical Cluster

$$
N_{\rm cluster} = \frac{R_{\rm lat}}{D} \times \frac{1}{\alpha} \times \frac{1}{K_{\rm geom}} \approx 8.41 \times 10^5
$$

$$
M_{\rm super} = M_{\rm DM}^{(\rm intermediate)} \times N_{\rm cluster}^{1/3} \approx 10.5\,{\rm TeV}
$$

(The difference between 10.5 TeV and the previously quoted 12.68 TeV is attributed to a refined choice of the correction coefficient.)

---

## 6. Plasma Resonance Factors

**Perpendicular orientation**

$$
\Gamma_\perp \approx 0.221
$$

**Parallel orientation (with boost)**

$$
{\rm Boost} \approx 15.2, \qquad \Gamma_\parallel = \Gamma_\perp \times {\rm Boost} \approx 3.36
$$

---

## 7. Knee Energy – Intermediate Result

$$
E_{\rm knee}^{(\rm intermediate)} = M_{\rm super} \times \Gamma_\parallel \approx 35.3\,{\rm TeV} = 0.035\,{\rm PeV}
$$

An additional aggregation factor of order ~114 is then introduced to bring the prediction to 4.02 PeV. The author links this factor to the ratio of the number of clusters in the Milky Way to the cosmic total. Independent derivation of this factor from first principles is still required.

---

## 8. Comparison Table (as presented by the author)

| Observatory          | Reported knee (PeV) | Uncertainty | Theory (PeV) | Difference |
|----------------------|---------------------|-------------|--------------|------------|
| Pierre Auger         | 4.0                 | 0.3         | 4.02         | 0.02       |
| KASCADE-Grande       | 3.7                 | 0.2         | 4.02         | 0.32       |
| Telescope Array      | 4.5                 | 0.5         | 4.02         | 0.48       |

---

## 9. Summary of Numerical Chain (Author’s Claim)

| Step | Quantity                      | Value          | Unit   |
|------|-------------------------------|----------------|--------|
| 1    | Base soliton energy           | 8516.649       | eV     |
| 2    | Raw DM mass                   | 23.73          | GeV    |
| 3    | Intermediate DM mass          | ~111.3         | GeV    |
| 4    | Target DM mass                | ~12.68         | TeV    |
| 5    | N_cluster                     | 8.41e5         | –      |
| 6    | N^{1/3}                       | 94.4           | –      |
| 7    | Super-soliton mass            | ~10.5          | TeV    |
| 8    | Γ_∥                           | 3.36           | –      |
| 9    | Intermediate knee             | 0.035          | PeV    |
| 10   | Final knee (after aggregation)| 4.02           | PeV    |

---

## 10. Critical Remarks for Scientific Evaluation

- Multiple multiplicative factors (S ≈ 4.69, Boost ≈ 15.2, aggregation factor ≈ 114, and the choice of the 1/3 power) are required to connect the base lattice calculation (~24 GeV) to both the 12.68 TeV dark-matter target and the ~4 PeV knee.
- The claim that “no free parameters are introduced” is difficult to sustain while successive correction coefficients are adjusted to recover the desired observational numbers.
- A rigorous derivation that fixes every numerical coefficient uniquely from the lattice geometry, without reference to the final observational targets, is still missing.
- Direct-detection experiments remain the cleanest falsification channel: a null result at 12.68 TeV with the predicted cross-section would challenge the framework independently of the cosmic-ray interpretation.

---

**Repository:** https://github.com/azhoseinali-ui/Harmonic-Lattice-Theory  
**Related documents:** STATEMENT.md, ENGLISH_SCIENTIFIC_STATEMENT.md, Cosmic_Ray_Knee_Response.md

This file is provided for archival and further development purposes. It does not constitute an endorsement of the numerical consistency claimed herein.

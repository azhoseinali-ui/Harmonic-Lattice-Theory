# Independent Check of the Proposed Lattice – D3-brane Correspondence

**Date:** 26 August 2026

---

## Author’s Table (summary)

| Lattice parameter | Claimed string-theory counterpart | Claimed relation |
|-------------------|-----------------------------------|------------------|
| $N_E = 240$       | Rank $N$ of $U(N)$                | $N = 120$        |
| $N_V = 60$         | Volume of $S^5$                   | direct identification |
| $R_{\rm lat}=2^{18}$ | String coupling $g_s$           | $g_s = 2^{-18}$  |
| $D=80$             | $R_{\rm AdS}/\alpha'$             | via $(4\pi g_s N)^{1/4}$ |
| $\alpha=1/137.036$ | $1/(4\pi g_s N)$                  | exact match claimed |

---

## Arithmetic verification of the key claim for $\alpha$

$$
g_s = 2^{-18} = \frac{1}{262144} \approx 3.814697 \times 10^{-6}
$$

$$
4\pi g_s N = 4\pi \times 2^{-18} \times 120 \approx 12.566371 \times 3.814697\times 10^{-6} \times 120
$$

$$
12.566371 \times 3.814697\times 10^{-6} \approx 4.794 \times 10^{-5}
$$

$$
4.794 \times 10^{-5} \times 120 \approx 0.005753
$$

$$
\frac{1}{4\pi g_s N} \approx \frac{1}{0.005753} \approx 173.8
$$

**Result:** The expression evaluates to approximately **173.8**, not 137.036. The claimed equality does not hold.

---

## Conceptual remarks

- In AdS/CFT the combination $4\pi g_s N$ (or $g_{\rm YM}^2 N$) is the ’t Hooft coupling, a dimensionless parameter of the dual gauge theory. It is **not** equal to the QED fine-structure constant $\alpha \approx 1/137$.
- Setting $g_s = 1/R_{\rm lat}$ has no standard justification in string theory.
- Identifying the integer 60 with the volume of $S^5$ confuses a dimensionless lattice count with a dimensionful geometric volume.
- The DBI action written on a discrete C60 graph is a formal replacement; it does not by itself determine the numerical values of the earlier Lagrangian coefficients $m_\phi$, $\lambda$, $\kappa$, $g$.

---

## Conclusion

The central numerical claim ($\alpha = 1/(4\pi g_s N)$ with the stated lattice values) is arithmetically incorrect by about 27 %. The remaining identifications are non-standard and do not follow uniquely from either the lattice geometry or type-IIB string theory. Consequently the proposed correspondence does not yet provide a consistent embedding of the Harmonic Lattice parameters into a D3-brane / AdS/CFT framework.

**Repository:** https://github.com/azhoseinali-ui/Harmonic-Lattice-Theory

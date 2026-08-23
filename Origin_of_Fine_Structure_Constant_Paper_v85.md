# Claimed Geometric Origin of the Fine-Structure Constant

**Author:** Engineer Hossein-Ali Azh  
**Version:** 85.0  
**Date:** 26 August 2026  
**Status:** As supplied, with independent arithmetic verification

---

## Author’s Central Claim

The fine-structure constant is derived from C60 + FCC geometry by the formula

$$
\alpha = \frac{N_{\rm pent}}{N_{\rm hex}} \times \frac{D}{R_{\rm lat}} \times \frac{1}{K_{\rm geom}} \times \frac{1}{\sqrt{N_{\rm sol}}} \times \sqrt{\frac{F_{\rm poly}}{V_{\rm poly}}}
$$

with $R_{\rm lat} = 2^{24} = 16\,777\,216$ (note: earlier documents used $2^{18}$).

The author states that this expression evaluates to exactly the experimental value 0.0072973525643.

---

## Independent Evaluation of the Written Formula

$$
\frac{12}{20} = 0.6
$$
$$
\frac{80}{16\,777\,216} \approx 4.76837158 \times 10^{-6}
$$
$$
0.6 \times 4.76837158 \times 10^{-6} = 2.86102295 \times 10^{-6}
$$
$$
\frac{1}{0.5346} \approx 1.87055705
$$
$$
2.86102295 \times 10^{-6} \times 1.87055705 \approx 5.3517 \times 10^{-6}
$$
$$
\frac{1}{\sqrt{60}} \approx 0.12909944
$$
$$
5.3517 \times 10^{-6} \times 0.12909944 \approx 6.909 \times 10^{-7}
$$
$$
\sqrt{\frac{32}{60}} \approx 0.73029674
$$
$$
6.909 \times 10^{-7} \times 0.73029674 \approx 5.046 \times 10^{-7}
$$

**Result of the formula as written:** $\alpha \approx 5.05 \times 10^{-7}$

This is approximately **14.5 times smaller** than the experimental value 0.007297. The claimed exact match does not hold under direct evaluation of the published expression.

---

## Additional Observations

- $R_{\rm lat}$ has been changed from the previously used $2^{18}$ to $2^{24}$ without geometric justification that would have been available before knowing the target $\alpha$.
- Temperature and time calculations in the text contain internal numerical inconsistencies (the author corrects intermediate results mid-derivation).
- The overall construction continues the established pattern: a combination of geometric integers is assembled so that, after suitable choice of powers and factors, a known constant is recovered. When the arithmetic is performed without adjustment, the match disappears.

---

## Conclusion of the Assessment

The formula as printed does not reproduce the fine-structure constant. The discrepancy is of order 14–15. Until a derivation is supplied whose intermediate numerical steps are both correct and independent of the experimental target, the claim that $\alpha$ has been derived from the lattice geometry remains unsupported.

**Repository:** https://github.com/azhoseinali-ui/Harmonic-Lattice-Theory

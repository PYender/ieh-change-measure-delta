# ieh-change-measure-delta
IEH + Δ reframes cosmic evolution without “past–present–future.” Age_Δ = w_a·Δ_a + w_T·Δ_T stays monotonic through expansion→implosion. The edge is unseen because implosion-dominated mixing blocks coherent outward signals, while observational inertia can briefly mimic continued expansion.
# Implosive Edge Hypothesis (IEH) and the Change Measure Δ — concept note (open for expert review)

**Short abstract**  
This concept note introduces the Implosive Edge Hypothesis (IEH) together with an orientation-free change measure Δ for cosmological evolution. Instead of “time,” we use Δ_a = ∫ |d ln a| and Δ_T = ∫ |d ln T_CMB|, and define an operational age Age_Δ = w_a · Δ_a + w_T · Δ_T, which remains **monotonic** through both expansion and implosion. IEH models the “edge” of the universe as an implosion-dominated mixing zone Σ that blocks coherent outward transmission; **observational inertia** (μ, τ_inertia) explains why observations can still look expansion-like during transitions. The note lists falsifiable predictions (redshift-drift sign reversal, CMB trend reversal, phase decoherence, Δ_T–Δ_a hysteresis) and a minimal measurement protocol. It is open for expert review.

## Key formulas (Unicode)
Δ_a = ∫ |d ln a|  Δ_T = ∫ |d ln T_CMB|  
Age_Δ = w_a · Δ_a + w_T · Δ_T  
H_eff = μ · H_+ + (1 − μ) · H_−  with H_+ > 0, H_− < 0  
dχ_obs/dλ = (χ_true − χ_obs) / τ_inertia

## Unified symbols & terms (Unicode, brief)
- **χ ∈ {+1, −1}** — global orientation of change (+1 expansion, −1 implosion).  
- **μ ∈ [0, 1]** — line-of-sight expansion fraction through Σ (1−μ samples implosion).  
- **τ_inertia > 0** — observational inertia timescale (lag).  
- **Σ** — mixing zone (“edge”): outward radiation fails to develop net divergence; phase information is lost (hence no coherent outward signal).  
- **a** — scale factor. **T_CMB** — CMB temperature (≈ 2.725 K today).  
- **Δ_a, Δ_T** — accumulated log-changes of a and T_CMB.  
- **Age_Δ** — operational age of change (linear in Δ_a, Δ_T).  
- **z** — redshift; **ż** — redshift drift, ż = dz/dt_obs.

## Minimal measurement protocol (sketch)
1. **Zero point**: set Age_Δ(today) = 0 at (a₀, T₀).  
2. **Accumulate Δ from observables**:  
   Δ_a = |ln(a/a₀)| = |ln((1+z₀)/(1+z))|; Δ_T = |ln(T_CMB/T₀)|.  
3. **Infer orientation and inertia**:  
   χ_obs from the sign of ż and the trend of T_CMB (↓ expansion, ↑ implosion);  
   μ via joint fits of ż, Hubble-diagram curvature, and phase-coherence metrics (EM/GW);  
   τ_inertia from the delay between the ż sign flip and the T_CMB trend reversal.  
4. **Report**: Age_Δ (monotonic), χ_obs, and (μ, τ_inertia); infer χ_true.

> Note: The relation `H_eff = μ · H_+ + (1 − μ) · H_−` is a **linear mixing heuristic** along a sightline; in general μ = μ( n̂, z ) may vary with direction and depth.

## Distinct predictions (falsifiable)
- **Redshift-drift sign reversal** when χ_true flips; during inertia, mixed signs across directions due to varying μ( n̂ ).  
- **CMB trend reversal**: T_CMB stops decreasing and starts increasing (with possible delay ≈ τ_inertia).  
- **Phase decoherence at Σ**: rising phase dispersion at the highest redshifts (EM/GW).  
- **Hysteresis between Δ_T and Δ_a** during the transition.

## Repository layout
/ (root)  
├── IEH_ChangeMeasure_Delta_concept_note_v1.0.pdf # main PDF  
├── figures/                     # optional figures (PNG/SVG/PDF)  
├── tex/                       # optional TeX sources (if used)  
├── LICENSE                    # e.g., CC BY 4.0  
└── README.md

**Concept DOI:** https://doi.org/10.5281/zenodo.17373020
**This version DOI (v1.0):** https://doi.org/10.5281/zenodo.17373021
## How to cite
M. Wlodarczyk, “**Implosive Edge Hypothesis (IEH) and the Change Measure Δ — concept note**,” Zenodo, v1.0, 2025. DOI: https://doi.org/10.5281/zenodo.17373021.

**BibTeX**
@misc{ieh_delta_concept_v1,
  author       = {Wlodarczyk, Mariusz},
  title        = {Implosive Edge Hypothesis (IEH) and the Change Measure Δ — concept note},
  year         = {2025},
  version      = {v1.0},
  publisher    = {Zenodo},
  doi          = {[10.5281/zenodo.17373021)},
  url          = {[https://doi.org/10.5281/zenodo.17373021)}
}

## License
Text and figures: **CC BY 4.0** (Creative Commons Attribution 4.0).  
If any code/scripts are included, consider **MIT** or **Apache-2.0** for them.

## Contact
Author: **Mariusz Wlodarczyk**
Contact: **mariusz.wlodarczyk@hotmail.com**

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17373021.svg)](https://doi.org/10.5281/zenodo.17373021)
**Latest release (v1.0.2):** https://doi.org/10.5281/zenodo.17373021

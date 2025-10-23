# Planck-Cell Electromagnetics

The canonical archive is DOI: 10.5281/zenodo.17217107  
This release (version DOI): 10.5281/zenodo.17421580  
Git: https://github.com/langstaffchristopherm-ops/Planck-Cell_Electromagnetics (commit abc1234). Version: v2.0.2  

LaTeX sources for the Planck-Cell S/t framework paper deriving electromagnetic
coupling as a fractional capacity share of the universal tick throughput.
Defines the fine-structure constant α = Q_EM / Q_max and the suppression
law for wavelength-dependent residuals r(λ) ≲ A(ξ_g/λ)^p.
Demonstrates consistency of the model with vacuum impedance, dispersion,
and photon-mass bounds.

## Sections
Each paper follows a modular layout under other_tex/, assembled via main.tex:
- Abstract — concise summary of claims and results  
- Introduction — motivation, context, and relation to prior works  
- Notation — tick-based units, entropy conventions, and symbol list  
- Scope and Falsifiability — domain of applicability and pre-registered tests  
- Results / Derivations — main relations and proofs  
- Discussion — interpretation and empirical comparison  
- Zenodo Links — cross-references to companion papers and datasets  
- Acknowledgements — credits and institutional notes  

## Related Zenodo Records
- Temporal Relativity (ΔS = Δτ) — https://doi.org/10.5281/zenodo.17119049  
- Planck-Cell Kinematics — https://doi.org/10.5281/zenodo.17168478  
- Planck-Cell Mass — https://doi.org/10.5281/zenodo.17209646  
- Planck-Cell Gravity — https://doi.org/10.5281/zenodo.17210232  
- Planck-Cell Thermal Physics — https://doi.org/10.5281/zenodo.17211721  
- Planck-Cell Electromagnetics — https://doi.org/10.5281/zenodo.17217107  
- Planck-Cell Expansion — https://doi.org/10.5281/zenodo.17216181  

## Build
To compile the PDF from source:
```bash
latexmk -pdf -interaction=nonstopmode main.tex

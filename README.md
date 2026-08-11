# Characterizing Perfect Truthfulness in Continuous Online Calibration

## Abstract

Recent work asks whether a sequential calibration measure can be perfectly truthful, complete, and sound. Additive proper losses are perfectly truthful but not complete. Subsampled calibration errors are complete and sound but only approximately truthful. We prove that this gap is unavoidable for every continuous measure that observes only the realized forecast path. Our main result characterizes all such perfectly truthful measures on any finite outcome alphabet. Every one is a sum of one-step proper losses, with a possibly different loss at each history. If the measure vanishes on every perfect deterministic forecast, these losses admit a nonnegative canonical normalization. This yields a finite-sample comparison: under i.i.d. truth $p$, the expected loss of a constant report $q$ is at most $\kappa(p,q)$ times truthful loss, where $\kappa(p,q)=(\max_i p_i/q_i)(\max_i q_i/p_i)$. For binary outcomes this is the odds ratio, and the constant is sharp. Completeness makes truthful loss sublinear, so the comparison contradicts the linear wrong-report loss required by soundness. In contrast, a recent perfectly truthful batch measure has a loss ratio that grows linearly with sample size. The result therefore identifies a strict batch versus online boundary for exact truthful calibration.

## Keywords

online calibration, truthfulness, continuous forecasts, incentive compatibility, sequential prediction, characterization

## Files

- `main.pdf`, `supplement.pdf`
- `main.tex`, `supplement.tex`
- `references.bib`
- `aistats2027.sty`, `fancyhdr.sty`
- `main.pdf.ots`, `supplement.pdf.ots`, `README.md.ots` OpenTimestamps priority proofs

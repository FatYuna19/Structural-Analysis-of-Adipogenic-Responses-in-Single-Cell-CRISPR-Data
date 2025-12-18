CrunchDAO Obesity — Geometric Perturbation Analysis (v4)
======================================================

Overview
--------
This directory contains frozen artifacts produced by a fully
deterministic, perturbation-level geometric analysis of gene
expression responses in the CrunchDAO Obesity Challenge dataset.

No model fitting, prediction, or causal inference is performed.
All results are descriptive and evaluated at the perturbation level.

What Was Done
-------------
1. Constructed perturbation-level mean expression deltas
   relative to a fixed control reference.
2. Identified a dominant geometric direction (PC1) in gene space.
3. Falsified this direction against random and orthogonal nulls.
4. Evaluated alignment with external adipogenesis programs.
5. Demonstrated necessity (not sufficiency) via constraint testing.
6. Quantified residual structure and explicit failure cases.
7. Verified generalization via holdout validation.
8. Froze artifacts, provenance, and claims.

What Was NOT Done
-----------------
- No causal claims
- No regulatory network inference
- No single-cell prediction
- No biological interpretation beyond geometry

Reproducibility
---------------
All numerical artifacts are fingerprinted with SHA-256 hashes.
Exact package versions, system information, and input data hashes
are recorded in provenance.json.

Integrity
---------
Artifacts were reloaded from disk and verified against their
recorded fingerprints. See execution_manifest.json for details.

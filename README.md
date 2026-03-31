# Synthetic Data Creates an Illusion of Validity but Fails as Clinical Evidence

This repository provides analysis workflows and evaluation frameworks supporting the findings of our study on synthetic data validity in clinical inference.

## Overview

Synthetic data is widely used to replicate real-world datasets. While existing evaluations focus on statistical similarity, this study examines whether synthetic data preserves **evidence-level consistency** required for clinical inference.

We demonstrate that:

* Synthetic data can closely match marginal distributions
* Structural dependencies may degrade
* Evidence-level inference (feature importance, subgroup stability) fails

## Repository Contents

* `data_schema.md`
  Description of variables and data structure (no patient-level data included)

* `workflow.md`
  Step-by-step analysis pipeline, including:

  * data construction
  * synthetic data generation (CTGAN, Copula)
  * evaluation framework (distribution, structure, evidence)

* `notebooks/figure_pipeline.ipynb`
  Reproducible workflows for generating Figures 2–4

## Data Availability

Due to privacy and institutional regulations, the original clinical dataset is not publicly available.

## Code and Reproducibility

All analyses were conducted using standard open-source libraries in Python and R.
This repository provides transparent workflows to enable inspection and partial reproducibility of the study design.

## Citation

If you use this work, please cite:

*Synthetic Data Creates an Illusion of Validity but Fails as Clinical Evidence* (under review)

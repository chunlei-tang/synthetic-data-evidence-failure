# Analysis Workflow

## 1. Data Construction

* Patient-level baseline dataset
* First-available-record strategy for labs
* Missing values handled via median imputation

## 2. Synthetic Data Generation

* CTGAN (deep generative model)
* Gaussian Copula (statistical baseline)
* Same schema and sample size as real data

## 3. Distribution Evaluation

* KDE comparison
* Kolmogorov-Smirnov test
* Total Variation Distance (categorical variables)

## 4. Structural Evaluation

* Correlation matrix comparison
* Focus on cross-type dependencies

## 5. Evidence-Level Evaluation (TSTR)

* Train on synthetic, test on real
* Feature importance comparison
* Subgroup stability analysis

## 6. Key Finding

Synthetic data preserves statistical similarity but fails to maintain evidence-level consistency required for clinical inference.

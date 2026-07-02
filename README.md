# Value Area Shape Classification

Machine learning that classifies market-profile **value-area shapes** (D, P, b and flat) in NQ futures.

Completed for the *Machine Learning & Advanced Python* module at Dublin City University.

## What I did

- Manually labelled a dataset of intraday volume profiles
- Engineered six statistical features from the volume-at-price distribution (skewness, kurtosis, RMS, and others)
- Trained and compared four classification models

**Result:** the best model — K-Nearest Neighbours — reached **97.9% accuracy** on clearly defined shapes.

## Contents

- `market_profile_classification.ipynb` — full analysis notebook
- `Data/` — labelled volume profiles and dataset

*Python · pandas · scikit-learn*

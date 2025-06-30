# One-Class Models for Financial Risk Classification

This repository contains the code used in the MSc thesis *Application of One Class Models for Financial Risk Classification*.

## Overview

The project explores the use of One Class classification models to detect financial risk in highly imbalanced data settings. The code is structured into two notebooks:

- `phase1_phase31.ipynb`: Implements Phase 1 using 13 expert selected features, and Phase 3.1 with hybrid models including anomaly scores.
- `phase2_phase32.ipynb`: Implements Phase 2 using the full feature set with automatic preprocessing, and Phase 3.2 with hybrid models.

The notebooks are already executed. Due to confidentiality, all data has been removed and some variable names appear blank or incomplete. 

## Installation

Dependencies are listed in the `requirements.txt` file. You can install them with:

```bash
pip install -r requirements.txt
```

Python 3.10 or higher is required.

## Notes

- The notebooks assume the availability of preprocessed data structures which are not included.
- Anomaly detection models used include: One-Class SVM, Isolation Forest, and Approximate Polytope Ensemble (APE).

## Disclaimer

This repository does not contain any proprietary or confidential data. It is shared for academic and educational purposes only.

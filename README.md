# Structural-to-AI Policy Learning for Multichannel Retail Decision Making

This repository accompanies the manuscript submitted to the 
Journal of Retailing and Consumer Services.

## Files

- structural_ai_multichannel.ipynb  
  End-to-end implementation:
  - Structural model specification
  - Synthetic instance generation (10,000 instances)
  - Policy learning (MLP)
  - Out-of-sample evaluation
  - Computational benchmark

- sim_multichannel_fast_relprice_10k.csv  
  Pre-generated synthetic dataset (10,000 instances)

## Reproducibility

All experiments use fixed random seed:

SEED = 2025

Running the notebook from top to bottom reproduces all results.

## Environment

Python 3.12 recommended.  
See requirements.txt for dependencies.

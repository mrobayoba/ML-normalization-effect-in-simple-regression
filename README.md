# Normalization Effect in Simple Linear Regression

> A reproducible numerical experiment comparing gradient-descent convergence on raw vs. min-max normalized input features, implemented from scratch using only NumPy and Matplotlib.

## Requirements

| Dependency | Version |
|------------|---------|
| Python | 3.8+ |
| `numpy` | any recent |
| `matplotlib` | any recent |

> Both libraries are pre-installed in Google Colab — no setup required.

## Usage

**Google Colab** (recommended)

1. Upload `normalization_analysis.ipynb` to [colab.research.google.com](https://colab.research.google.com).
2. Select **Runtime → Run all**.

**Local**

```bash
pip install numpy matplotlib
jupyter notebook normalization_analysis.ipynb
```

## Notebook Overview

| # | Section | Description |
|---|---------|-------------|
| 1 | Imports | NumPy and Matplotlib |
| 2 | Experiment design | Two-run comparison strategy |
| 3 | Data generation | Synthetic linear data with wide input range |
| 4 | Model functions | Gradient descent implemented from scratch |
| 5 | Experiment 1 | Same learning rate — loss curves and fitted lines compared |
| 6 | Experiment 2 | Raw model retrained with reduced learning rate |
| 7 | Conclusions | Summary of observed differences |


# The Hate Busters at MultiPRIDE

### Automatic Identification of Reappropriated Slurs in Multilingual LGBTQ+ Discourse (EVALITA 2026)

This repository contains the **code, notebooks, and data processing resources** used in HateBusters' EVALITA 2026 submission:

> *The Hate Busters at MultiPRIDE: Automatic Identification of Reappropriated Slurs in Multilingual LGBTQ+ Discourse*

The project focuses on the **automatic detection of reappropriated slurs** in multilingual LGBTQ+ discourse, supporting:

* reproducibility of the experimental results
* transparent research practices
* future work on inclusive and context-aware hate speech detection

---

## Repository Structure

```
.
├── XLMR_TaskA_TaskB.ipynb   # XLM-RoBERTa (Task A + Task B)
├── TaskA_Sparse.ipynb       # Traditional Models (Task A)
├── TaskB_Sparse.ipynb       # Traditional Models (Task B)
├── data/                    # CSV datasets used in the experiments
└── README.md
```

---

## Data

The repository includes the **CSV files used in the experiments**, corresponding to the datasets provided within the MultiPRIDE shared task framework.

If redistribution restrictions apply, only **processed or derived data** are included.
Please refer to the official shared task resources for the original datasets.

---

## Reproducibility

To reproduce the results reported in the paper:

1. Clone the repository
2. Install the required Python dependencies
3. Run the notebooks in the following order:

   * `XLMR_TaskA_TaskB.ipynb`
   * `TaskA_Sparse.ipynb`
   * `TaskB_Sparse.ipynb`

All experimental settings and preprocessing steps are documented inside the notebooks.

---

## Requirements

Typical environment:

* Python ≥ 3.9
* Jupyter Notebook
* Common NLP and ML libraries (e.g., pandas, numpy, scikit-learn, transformers)

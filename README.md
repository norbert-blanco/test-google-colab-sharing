# DACFE notebooks

Python/Jupyter notebooks for the DACFE course, converted from the original MATLAB Live Scripts. Each notebook runs directly in Google Colab with no setup, using only `numpy`, `pandas` and `matplotlib` (all preinstalled in Colab).

## Notebooks

| Notebook | Description | Open in Colab |
|---|---|---|
| `notebooks/DACFE_Ex201.ipynb` | Apparent engineering properties of a laminate | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/norbert_blanco/test-google-colab-sharing/blob/main/notebooks/DACFE_Ex201.ipynb) |
| `notebooks/DACFE_Ex401.ipynb` | Tsai-Wu failure criterion in a laminate | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/norbert_blanco/test-google-colab-sharing/blob/main/notebooks/DACFE_Ex401.ipynb) |

**Before pushing:** replace `REPLACE_WITH_USERNAME` and `REPLACE_WITH_REPO` above with your actual GitHub username and repository name so the badges link correctly.

## For students

Click the "Open in Colab" badge for the notebook you want. It opens directly in your browser with no installation needed.

To keep your own edits, use **File > Save a copy in Drive** (or **File > Save a copy in GitHub** if you have a GitHub account) right after opening — otherwise your changes won't be saved when you close the tab, since you're viewing the instructor's copy.

## Repository structure

```
.
├── README.md
├── requirements.txt
└── notebooks/
    ├── DACFE_Ex201.ipynb
    └── DACFE_Ex401.ipynb
```

## Running locally (optional)

If you prefer Jupyter on your own machine instead of Colab:

```bash
pip install -r requirements.txt
jupyter notebook
```

## Updating notebooks

Each notebook was generated from the corresponding MATLAB Live Script and verified to reproduce the original numerical output. When pushing an updated version, keep the filename the same so existing Colab links (and the badges above) keep working; students will see the latest committed version the next time they open or reload the link.

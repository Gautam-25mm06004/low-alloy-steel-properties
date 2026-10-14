# Mechanical Properties of Low-Alloy Steels

Predicts tensile strength, yield strength and elongation of low-alloy steels from composition and test temperature: exploratory analysis, model training and a fuller property-prediction study.

## Contents

| File | What it does |
|---|---|
| `notebooks/low_alloy_steel_property_prediction.ipynb` | Mechanical Properties of Low-Alloy Steels |
| `notebooks/01_exploratory_analysis.ipynb` | Importing Libraries |
| `notebooks/02_model_training.ipynb` | Importing Libraries |

Notebooks are saved with the outputs of their last run, so results and figures can be read on GitHub without running anything.

## Data

Kaggle "Mechanical properties of low-alloy steels" (`Low-alloy-steel-data.csv`). Place it next to the notebooks.

## How to run

The notebooks were developed on Google Colab. Upload a notebook to Colab (File → Upload notebook) and run the cells in order; the first cells install anything missing. To run locally in VS Code instead: `python -m venv .venv`, activate it, `pip install -r requirements.txt jupyter`, then open the notebook and pick the `.venv` kernel. Cells that mount Google Drive (`google.colab`) can be skipped locally if the data files are placed next to the notebook.

Python packages used: `catboost`, `ipython`, `joblib`, `lightgbm`, `matplotlib`, `numpy`, `pandas`, `scikit-learn`, `scipy`, `seaborn`, `xgboost` (see `requirements.txt`).

## License

MIT, see `LICENSE`.

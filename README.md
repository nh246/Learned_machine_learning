# Learned Machine Learning

A curated collection of Jupyter notebooks, datasets, and example outputs for learning data analysis, visualization, and machine learning. This repository is organized by topic/modules so students and self-learners can follow a clear learning path from EDA through modeling.

---

## Quick Links (start here)

- `1_EDA/` — Exploratory Data Analysis notebooks and reports
  - [M10/Mark_down.ipynb](1_EDA/M10/Mark_down.ipynb)
  - [M11/Pandas4.ipynb](1_EDA/M11/Pandas4.ipynb)
  - [M13/auto_eda.ipynb](1_EDA/M13/auto_eda.ipynb)

- `2_Data_Visualization/` — Plotting and interactive visualization
  - [M24/01_plotly.ipynb](2_Data_Visualization/M24/01_plotly.ipynb)
  - [M26/AnimatedPlots.ipynb](2_Data_Visualization/M26/AnimatedPlots.ipynb)

- `3_Data_Scaling/` — Scaling and encoding examples
  - [1_Feature_scaling.ipynb](3_Data_Scaling/1_Feature_scaling.ipynb)
  - [2_Feature_Encoding.ipynb](3_Data_Scaling/2_Feature_Encoding.ipynb)

- `4_Numpy/` — NumPy fundamentals
  - [M28/Intro_numpy.ipynb](4_Numpy/M28/Intro_numpy.ipynb)

- `5_Mathematics/` — Linear algebra and statistics notebooks
  - `Linear_Algebra/linearAlgebra.ipynb` — Linear algebra for ML
  - `Statistics/` — ANOVA, MANOVA, correlation, hypothesis tests

- `6_Supervised_ML/` — End-to-end modeling examples
  - `Heart_Disease_Prediction/H_D_P.ipynb` — Full workflow: EDA, imputation, modelling
  - `Heart_Disease_Prediction/Function_to_impute_null.ipynb` — Imputation helpers
  - `M75/10_linear_regression.ipynb`, `M80/15_random_forest.ipynb`
  - `saved_models/` — Directory for saved model artifacts

- `7_UnSupervised_ML/` — Unsupervised techniques
  - `M101/20_PCA.ipynb` — PCA demonstrations and visualizations

If a listed notebook link doesn't open in your environment, open the module folder and pick the notebook that matches the topic — some files may have slightly different names or extra copies.

---

## Purpose & Audience

This repository is intended for learners who want hands-on practice with common data science tasks: exploring datasets, visualizing insights, preprocessing, and building simple ML models. Notebooks are written as examples and teaching aids rather than production-ready pipelines.

## Quick setup (Windows)

1. Clone the repository:

```cmd
git clone <repo-url>
cd Learned_machine_learning
```

2. Create and activate a virtual environment (recommended):

```cmd
python -m venv .venv
.venv\Scripts\activate
```

3. Install dependencies:

```cmd
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

4. Start Jupyter Lab / Notebook or open the repository in VS Code and choose the `.venv` kernel:

```cmd
jupyter lab
```

Notes:
- If VS Code shows "Import X could not be resolved", confirm the selected interpreter matches the env where you installed packages.
- Many notebooks rely on relative dataset paths (e.g., `.../Dataset/*.csv`); open the notebook from the repo root or its folder to keep relative paths valid.

---

## Recommended learning path

1. `1_EDA/` — Start here to learn dataset inspection, summary statistics, and quick visual checks.
2. `2_Data_Visualization/` — Study plotting (static and interactive) and how to present findings.
3. `3_Data_Scaling/` & `4_Numpy/` — Learn preprocessing and array operations used by ML models.
4. `6_Supervised_ML/` — Follow one end-to-end notebook (e.g., Heart Disease Prediction) to see a full workflow.

## Contributing

- Add a README inside any module folder you add, documenting dataset source, license, and which notebooks use it.
- If you add notebooks, prefer clear filenames and include a short description at the top markdown cell.

## Ideas I can help with

- Generate a pinned `requirements.txt` with tested package versions.
- Create a `notebooks-index.md` that automatically lists all notebooks with links.
- Add a small `setup_windows.bat` to automate venv creation and dependency install.

## License

This repository contains learning materials. If you want to distribute broadly, add a `LICENSE` file (MIT is a common permissive choice).

---


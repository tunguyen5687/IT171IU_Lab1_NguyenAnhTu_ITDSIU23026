# Additional datasets (IT171IU labs)

Public datasets used in the new (red) exercises. The notebooks look for them in `additional-data/` (next to the notebook or one folder up); if the folder is missing — for example on Google Colab — the helper `load_extra(name)` rebuilds the same table from scikit-learn or lifelines.

| File | Rows × columns | Response / label | Source | Used in |
|---|---|---|---|---|
| `diabetes.csv` | 442 × 11 | `progression` (disease progression after one year) | Efron et al. (2004), *Least Angle Regression*; `sklearn.datasets.load_diabetes(scaled=False)` | Labs 2, 4, 5 |
| `breast_cancer.csv` | 569 × 31 | `diagnosis` (malignant / benign) | Wisconsin Diagnostic Breast Cancer, UCI ML Repository; `sklearn.datasets.load_breast_cancer` | Labs 3, 7, 8, 12 |
| `wine.csv` | 178 × 14 | `cultivar` (3 classes) | UCI Wine data; `sklearn.datasets.load_wine` | Labs 3, 11 |
| `digits.csv` | 1797 × 65 | `digit` (0–9), 8×8 pixel intensities | UCI Optical Recognition of Handwritten Digits; `sklearn.datasets.load_digits` | Labs 8, 9, 11 |
| `rossi.csv` | 432 × 9 | `week` (time to re-arrest), `arrest` (event) | Rossi, Berk & Lenihan (1980); `lifelines.datasets.load_rossi` | Lab 10 |

## 🚀 How to Run & Reproduce

### 1. Local Execution (Self-Contained)
The project is fully self-contained with all 10-fold splits (`data/`), scalers (`scaler/`), and weights (`model/`) included.
- Open `ann-for-concrete-strength-prediction-v1.ipynb` in VS Code or Jupyter Notebook.
- Run all cells directly using local relative paths.

> **Precision Note:** A negligible variance at the 3rd decimal place ($\Delta < 0.005$ on MSE) between Kaggle and local execution is normal due to CPU floating-point rounding (IEEE 754).

### 2. Cloud Execution (Kaggle)
Run the original cloud notebook with one click:

[![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/noureddinebelmokhtar/ann-for-concrete-strength-prediction-v1)
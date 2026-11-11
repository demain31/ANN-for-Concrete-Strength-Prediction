## 🚀 How to Run

### 1. Run Locally
The repository includes all necessary files (`data/`, `scaler/`, and `model/`) to run everything offline:
- Open `ann-for-concrete-strength-prediction-v1.ipynb` in VS Code or Jupyter.
- Run all cells to execute the evaluation pipeline.
- **Interactive Prediction Form:** Use the interactive widget at the bottom of the notebook to enter custom mix proportions (cement, water, aggregates, age, etc.) and get real-time compressive strength estimates in MPa.

> **Dataset Scope:** The datasets in `data/` (train, val, test) are included solely for metric validation and reproducibility. Real-time inference relies exclusively on the pre-trained model weights, biases, and scalers.

> **Note on Precision:** Local scores match the Kaggle results up to two decimal places. Any tiny difference in the third decimal is just rounding across machines.

### 2. Run on Kaggle
You can also run the original notebook (including the interactive form) with one click:

[![Open In Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/noureddinebelmokhtar/ann-for-concrete-strength-prediction-v1)
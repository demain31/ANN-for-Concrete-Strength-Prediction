## 🚀 How to Run & Reproduce Results

You can reproduce the complete 10-fold cross-validation pipeline through two supported environments:

### 1. Standalone Local Execution (Self-Contained)
The repository is now **fully self-contained and completely independent of external cloud platforms**. All 10-fold cross-validation datasets (`data/`), pre-calculated transformation parameters (`scaler/`), and network weight matrices (`model/`) are bundled directly within the repository.

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/demain31/ANN-for-Concrete-Strength-Prediction.git
Open and execute ann-for-concrete-strength-prediction-v1.ipynb using VS Code, Jupyter Notebook, or your preferred local IDE.
The pipeline runs out-of-the-box using standardized relative paths without any manual path adjustments.
2. Cloud Execution via Kaggle (1-Click Run)
Alternatively, you can inspect and execute the original cloud kernel with pre-mounted Kaggle environments:
![Image](https://kaggle.com/static/images/open-in-kaggle.svg)
=======
🚀 How to Run & Reproduce Results
1. Local Execution (Fully Self-Contained)
The notebook is now fully functional locally out-of-the-box. All fold splits (data/), pre-calculated parameters (scaler/), and trained weights (model/) are packaged directly within this repository. You can execute ann-for-concrete-strength-prediction-v1.ipynb directly using VS Code, Jupyter Notebook, or your local IDE without any external cloud dependencies.
Note on Numerical Precision: A minor difference (starting from the third decimal place, e.g., 
Δ
<
0.005
Δ<0.005
) between the MSE obtained on Kaggle and the one computed locally is expected. This slight variance is strictly due to floating-point arithmetic precision and low-level CPU rounding routines (IEEE 754 standard) across different operating systems. It does not affect model performance or evaluation conclusions.
2. Cloud Execution on Kaggle (1-Click Run)
Alternatively, you can run the pipeline directly in the cloud on Kaggle:
![Image](https://kaggle.com/static/images/open-in-kaggle.svg)
Note: Running directly on Kaggle avoids manual path configuration, as all required input artifacts (01table.npy, w.npy, scalers, and fold splits) are already mounted in the working environment.
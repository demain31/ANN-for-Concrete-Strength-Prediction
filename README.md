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

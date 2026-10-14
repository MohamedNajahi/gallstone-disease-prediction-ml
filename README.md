# Gallstone Disease Prediction Using Machine Learning

This repository contains a Python based machine learning implementation for gallstone disease classification using clinical, laboratory, and bioimpedance data.

The project is based on the research paper *Early prediction of gallstone disease with a machine learning-based method from bioimpedance and laboratory data* by Esen et al. (2024).

The implementation uses Jupyter Notebook and Scikit-learn to explore the dataset, preprocess the data, train machine learning classifiers, and evaluate their performance.

## Reference Paper

**Title:** Early prediction of gallstone disease with a machine learning-based method from bioimpedance and laboratory data

**Authors:** Esen et al. (2024)

**Paper:** [doi.org/10.1097/MD.0000000000037258](https://doi.org/10.1097/MD.0000000000037258)



## Dataset

**Dataset:** Gallstone Dataset — UCI Machine Learning Repository

**Source:** [archive.ics.uci.edu/dataset/1150/gallstone-1](https://archive.ics.uci.edu/dataset/1150/gallstone-1)

The dataset contains clinical, laboratory, and bioimpedance measurements used for gallstone disease classification.

## Technologies

- Python
- Jupyter Notebook
- NumPy and Pandas
- Scikit-learn
- XGBoost
- Matplotlib and Seaborn

## How to Run

**1. Clone the repository**

```bash
git clone https://github.com/MohamedNajahi/gallstone-disease-prediction-ml.git
cd gallstone-disease-prediction-ml
```

**2. Create a virtual environment**

```bash
python -m venv .venv
```

Activate it on Windows:

```powershell
.\.venv\Scripts\Activate.ps1
```

**3. Install the dependencies**

```bash
pip install -r requirements.txt
```

**4. Start Jupyter Notebook**

```bash
jupyter notebook
```

**5. Open and run the notebook**

Open `Phase 2.ipynb` and select **Run All**.

Make sure `dataset-uci.csv` is in the same folder as the notebook.

## Reference

Esen et al. (2024). *Early prediction of gallstone disease with a machine learning-based method from bioimpedance and laboratory data*. Medicine.

[doi.org/10.1097/MD.0000000000037258](https://doi.org/10.1097/MD.0000000000037258)

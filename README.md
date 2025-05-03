# 🐧 Clustering Antarctic Penguin Species

This project applies K-Means clustering to the Palmer Penguins dataset to explore natural groupings in penguin species using unsupervised learning techniques.

## 📊 Dataset

The dataset includes physical attributes of penguins such as:
- Culmen (bill) length and depth (mm)
- Flipper length (mm)
- Body mass (g)
- Sex (encoded as dummy variables)

Dataset: `penguins.csv`

## 🔧 Process Overview

1. **Data Preprocessing**
   - Convert categorical variables into dummy variables
   - Handle missing values (if any)

2. **Feature Scaling**
   - Standardize features using `StandardScaler`

3. **Clustering**
   - Apply K-Means clustering to identify groups
   - Visualize results using `matplotlib`

## 📦 Dependencies

- `pandas`
- `matplotlib`
- `sklearn`

Install dependencies via pip:
```bash
pip install pandas matplotlib scikit-learn
```

## 🧪 How to Run
Open the `notebook.ipynb` in Jupyter or any compatible IDE and execute the cells step-by-step. Ensure `penguins.csv` is in the same directory.

## 📈 Output
* Clustered visualizations
* Scaled and encoded dataset
* Interpretation of cluster groupings

## 📁 Files
* `notebook.ipynb` – Jupyter notebook containing code and outputs
* `penguins.csv` – Raw dataset used for clustering

# Iris Species Analysis

## Problem / Research Question
Which flower measurements best distinguish the three Iris species
(setosa, versicolor, virginica), and how do the species differ?

## Dataset Source and Usage Permissions
The dataset is the built-in Iris dataset from scikit-learn
(`sklearn.datasets.load_iris`). It is a public, widely used dataset
with no personal or restricted information. No external download is
required, and it is freely usable for educational purposes.

## Methods and Tools
- Python 3
- pandas for data handling and group statistics
- matplotlib for visualization
- scikit-learn for loading the dataset
- Two visualizations:
  1. Boxplot of petal length by species
  2. Scatter plot of petal length vs petal width by species

## Key Findings and One Limitation
- Petal length is the most discriminative feature: setosa has clearly
  shorter petals, while versicolor and virginica are separable but
  slightly overlap.
- Limitation: The dataset is very small (150 samples) and clean, so
  the results may not generalize to real-world, noisy measurements.

## Instructions for Running the Analysis
1. Install dependencies: `pip install -r requirements.txt`
2. Open `iris_analysis.ipynb` in Jupyter Notebook.
3. Run all cells from top to bottom.
4. The script will generate `petal_length_boxplot.png` and
   `petal_scatter.png`.

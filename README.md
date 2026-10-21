# Iris Petal Measurements: An Exploratory Analysis

## Problem / Research Question
This project examines how petal length and width differ among the three Iris species (setosa, versicolor, virginica), and how clearly these measurements separate the species in visualizations.

## Dataset Source and Usage Permissions
The analysis uses the built-in Iris dataset from scikit-learn (`sklearn.datasets.load_iris`). It contains 150 flowers, with 50 observations for each species. 
- **Source:** UCI Machine Learning Repository (DOI: 10.24432/C56C76). 
- **License:** Creative Commons Attribution 4.0 International (CC BY 4.0), allowing sharing and adaptation with attribution.
- **Permissions:** No personal or restricted data is included. The notebook loads the dataset directly from scikit-learn, so no external CSV download is required.

## Methods and Tools
- **Python 3**
- **pandas:** For organizing data and calculating species averages.
- **matplotlib:** For generating the box plot and scatter plot.
- **scikit-learn:** For loading the dataset.
This project focuses on exploratory data analysis (EDA) and visualization, rather than training a predictive model.

## Key Findings and One Limitation
- **Key Findings:** Setosa has the shortest and narrowest petals on average (mean length: 1.462 cm; width: 0.246 cm). Versicolor (length: 4.260 cm; width: 1.326 cm) and virginica (length: 5.552 cm; width: 2.026 cm) are larger but overlap in part. Longer petals generally accompany wider petals, and petal length is a strong discriminator.
- **Limitation:** The dataset is very small (150 samples) and controlled, so the findings may not generalize to other iris species or flowers grown under different real-world conditions.

## Instructions for Running the Analysis
1. Clone this repository or download it as a ZIP file and extract it.
2. Ensure you have Python 3 installed. Open Terminal (or Anaconda Prompt) in the project folder.
3. Install dependencies: `pip install -r requirements.txt` (use `pip3` on Mac if needed).
4. Open Jupyter Notebook: `jupyter notebook`.
5. Open `iris_analysis.ipynb` and run all cells from top to bottom. The script will display the data preview, species averages, and generate the two visualizations (`petal_length_boxplot.png` and `petal_scatter.png`).

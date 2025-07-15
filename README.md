diff --git a/README.md b/README.md
--- a/README.md
+++ b/README.md
@@ -1,1 +1,36 @@
-# Chicago_data_visualization
+# Chicago Crime Data Visualization and Stratified Sampling
+
+## Overview
+This project analyzes and visualizes the Chicago Crime dataset (2001-present), focusing on crime trends, types, and locations. It also demonstrates stratified sampling techniques to create representative data subsets for statistical analysis and validation.
+
+## Features
+- **Data Exploration:** Visualizes crime counts by year and by primary type.
+- **Stratified Sampling:** Samples 10% of the dataset, stratified by year and crime type, ensuring representativeness.
+- **Statistical Validation:** Uses Chi-Square and Kolmogorov-Smirnov tests to compare distributions between the full and sampled datasets.
+- **Visualization:** Compares normalized distributions for key features (Arrest, Domestic, Primary Type, Location Description, Community Area) between the full and sampled data.
+
+## Dataset
+- **Source:** [Chicago Crime Dataset (Kaggle)](https://www.kaggle.com/datasets/chicago/chicago-crime)
+- **Additional Links:**
+  - [Google Drive Folder](https://drive.google.com/drive/folders/1e4PbcKjKJrJFjIXzD1nbcObAj2blkDYU?usp=drive_link)
+  - [Tableau Dashboard](https://public.tableau.com/views/ChicagoCrimeDashboard_17441311944260/HomePage?:language=en-US)
+
+## Usage
+1. **Requirements:**
+   - Python 3.x
+   - pandas, numpy, matplotlib, scikit-learn, scipy
+2. **Run the Analysis:**
+   - Open `sampling.ipynb` in Jupyter or VSCode.
+   - Follow the notebook cells to load, sample, analyze, and visualize the data.
+3. **Output:**
+   - The notebook generates plots and a sampled CSV (`sampled_chicago_crime_final.csv`).
+
+## Files
+- `sampling.ipynb`: Main analysis and sampling notebook.
+- `CommAreas_20250406.zip`: Community area data (optional, for advanced analysis).
+- `Report On Chicago Crime.pdf`: Project report.
+- `T_05_IDV_Final_Project_Done.pptx`: Project presentation.
+- `Dataset Link.pdf`: Dataset and dashboard links.
+
+## License
+This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

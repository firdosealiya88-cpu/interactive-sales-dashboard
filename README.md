# Week 6: Interactive Sales Dashboard Documentation

## 1. Project Overview & Objectives
This project provides an automated data analytics pipeline designed to ingest retail transaction streams and compile them into visual layers. Using dynamic plotting libraries, it identifies performance outliers, tracking sales velocities across target geographical zones.

## 2. Environment Setup Instructions
To initialize the software environment locally on your terminal:
1. Ensure Python 3.9+ is active.
2. Ingest the module requirements file layout:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analytical visualization orchestration compiler:
   ```bash
   python dashboard.py
   ```

## 3. Structural Hierarchy Mapping
* `dashboard.py` — The core script housing dataset arrays and visual generation pipelines.
* `requirements.txt` — Explicit package definitions required for grading module stability.
* `visualizations/` — Compiled target distribution folder containing pre-rendered assets.
  * `price_distribution_boxplot.png` (Static distribution metrics)
  * `correlation_heatmap.png` (Linear feature alignment heatmaps)
  * `regional_sales_violinplot.png` (Advanced density metrics charts)
  * `interactive_sales_trend.html` (Dynamic runtime Plotly tracking)
  * `interactive_product_segmentation.html` (Dynamic sunburst breakdown)

## 4. Algorithmic Specifications
* **Data Layer:** Managed via vectorized Pandas configurations handling type casting variables.
* **Exploratory Metrics Layer:** Seaborn engines isolate data outliers (Box Plots) and measure dependency coefficients (Heatmaps).
* **Interactive Frontend Engine:** Plotly compiles nested sunburst layers and tracking timelines embedded into standalone HTML wrappers.

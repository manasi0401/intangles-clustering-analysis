# Intangles Event Clustering - Python Analysis

This repository contains the Python-based clustering solution for the Intangles assignment using geolocation (latitude, longitude) and event duration data.

## 📁 Files

- `data.csv` – Input dataset containing event locations and durations
- `intangles_clustering.py` – Main Python script performing:
  - K-means clustering using haversine distance
  - Optimal cluster selection (Elbow Method)
  - Cluster-wise statistics (event count, average duration, etc.)
  - Data visualizations (scatter plots, bar charts, box plots)
  - CSV export of cluster assignments

## 🧠 What It Does

- Reads event data and parses location info
- Uses a custom K-Means algorithm to cluster geospatial data
- Determines the optimal number of clusters using SSE
- Generates insightful visualizations:
  - Event clusters by location
  - Event count per cluster
  - Duration distribution per cluster
- Saves the results in `clustered_output.csv`

## 🖼️ Output

All results, stats, and plots are visible when the code is run locally or in Google Colab.  
The code is self-contained and does not require external APIs or libraries

## ▶️ Run

```bash
python intangles_clustering.py

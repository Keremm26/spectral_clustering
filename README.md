# 🔍 Spectral Clustering on Synthetic Datasets

This project demonstrates the use of **Spectral Clustering** implemented in **MATLAB**, applied to synthetic datasets including circular, spherical, and spiral patterns. The goal is to cluster non-linearly separable data using graph-based clustering methods.

---

## 📁 Project Structure

```
.
├── data/
│   ├── Circle.csv
│   ├── Sphere.csv
│   └── Spiral.csv
├── report/
│   └── spectral_clustring_report.pdf
├── src/
│   └── spectral_clustring.m
└── instruction.txt
```

- `data/`: Contains the datasets in `.csv` format.
- `src/`: MATLAB implementation of the Spectral Clustering algorithm.
- `report/`: Detailed PDF report explaining the methodology, implementation, and results.
- `instruction.txt`: Additional project instructions.

---

## 📌 Features

- Spectral clustering with adjacency and Laplacian matrix construction.
- Works on complex shapes like spirals and rings.
- Eigen decomposition-based dimensionality reduction.
- K-means clustering on spectral embedding.
- Evaluation with plots and visualizations.

---

##  Algorithm Overview

1. **Load Data** from CSV files.
2. **Build Similarity Graph** using distance-based metrics.
3. **Compute Laplacian Matrix**.
4. **Extract Eigenvectors** of the Laplacian.
5. **Apply K-means** to cluster eigenvector representation.
6. **Visualize Results** for each dataset.

---

## 🛠 Dependencies

- MATLAB (tested on R2024a and R2024b)
- No additional toolboxes required

---

## 📄 Report

See `report/spectral_clustring_report.pdf` for methodology, visuals, and analysis.

---


## 📜 License

This project is licensed under the [MIT License](LICENSE).

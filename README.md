# Visual Assessment of Tendency (VAT)

This project implements the **VAT (Visual Assessment of Tendency)** algorithm to visually assess the clustering tendency in a dataset. It reorders the pairwise distance matrix and visualizes it as a grayscale image where clusters appear as dark blocks.

## 🧠 What is VAT?

Visual Assessment of Tendency (VAT) is a clustering evaluation technique used to detect natural grouping structures in data. By reorganizing the distance matrix, it helps visually identify cluster formations before applying any clustering algorithm.

## 📊 Dataset

This example uses a small real-life inspired dataset representing customer purchasing behavior:

## 🚀 How It Works

- **Compute Distance Matrix**: Calculates pairwise Euclidean distances between all data points.
- **Reorder the Matrix**: A greedy algorithm reorders rows and columns to group similar points.
- **Visualize**: Displays the reordered distance matrix as a grayscale heatmap. Clusters appear as dark blocks along the diagonal.


## 🧩 Dependencies

This project requires the following Python libraries:

- [numpy](https://numpy.org/)
- [scipy](https://scipy.org/)
- [matplotlib](https://matplotlib.org/)

You can install them using:

```bash
pip install numpy scipy matplotlib

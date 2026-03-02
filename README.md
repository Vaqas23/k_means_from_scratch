# K-Means Clustering from Scratch

A Python implementation of the k-means clustering algorithm built from scratch without using NumPy or scikit-learn.

## Features

- **Pure Python implementation** - Uses only the `math` module
- **Elbow method** - Automatically determines optimal number of clusters
- **Robust handling** - Includes input validation and empty cluster fallback
- **Visualization** - Matplotlib plot showing distance vs k value

## Usage

The notebook `cookie_plot_k_means_clustering.ipynb` demonstrates k-means clustering on cookie recipe data (19 recipes with 4 ingredient features: eggs, butter, sugar, flour).

### Running the Algorithm

```python
# Define your data as a list of lists
data = [
    [0.14, 0.14, 0.28, 0.44],
    [0.22, 0.1, 0.45, 0.33],
    # ... more data points
]

# Run k-means with k=3 clusters
result = k_means(data, 3)
```

The elbow plot shows that k=3 is the optimal number of clusters for this dataset.

## Algorithm Details

- **Initialization**: Cyclic assignment of points to clusters
- **Distance metric**: Euclidean distance
- **Convergence**: Stops when cluster assignments no longer change
- **Return value**: Sum of minimum distances (for elbow method)

## Requirements

- Python 3.x
- matplotlib

## About

This implementation was created as a learning exercise to understand the mechanics of k-means clustering without relying on machine learning libraries.

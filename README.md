This is a pure Python implementation of the k-means clustering algorithm. It includes both a standard k-means function that returns k clusters, and an implementation using the elbow method to determine the optimal number of clusters. I built this to understand how unsupervised learning algorithms work at a fundamental level before relying on libraries like scikit-learn.

The design prioritizes clarity and simplicity (quite hard given all the for loops). This means no external libraries beyond Python's built-in "math" module (except Matplotlib for plotting of course). I used Euclidean distance for clustering, handled edge cases like empty clusters, and implemented convergence detection to ensure the algorithm terminates properly.

This project deepened my understanding of clustering algorithms and reinforced core Python fundamentals. Please reach out if you have any questions.

This project explores and compares three clustering approaches:

- K-means++ (with kernel extensions)
- Hierarchical clustering
- Spectral clustering

## 1. K-means++

The K-means++ algorithm was implemented from scratch. Initially, it was tested on 2D datasets without kernels. Due to limitations with non-spherical data, kernel methods were introduced.

### Kernels used:
- Linear
- Polynomial (degrees 2–5)
- RBF
- Sigmoid

## 2. Hierarchical Clustering

The following linkage methods were implemented:

- Single linkage
- Complete linkage
- Average linkage
- Ward’s method

## 3. Spectral Clustering

Spectral clustering was implemented using three graph construction methods:

- k-nearest neighbors (kNN)
- Epsilon-neighborhood (ε)
- Fully connected graph




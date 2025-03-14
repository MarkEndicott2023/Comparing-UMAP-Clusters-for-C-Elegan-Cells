### Overview

This project applies an Autoencoder-based approach to dimensionality reduction and clustering in single-cell RNA sequencing (scRNA-seq) data. It compares a series of UMAP outputs from various dimensionality reduction techniques including PCA and a nueral network autoencoder generated by PyTorch.

### Current Features

- Preprocess scRNA-seq data using ScanPy
- Leiden clustering on autoencoder-based embeddings
- UMAP visualization to compare PCA vs. autoencoder
- Biological interpretation using marker genes

### Data Source

Calico Labs sc-RNA-seq data -> https://c.elegans.aging.atlas.research.calicolabs.com/data


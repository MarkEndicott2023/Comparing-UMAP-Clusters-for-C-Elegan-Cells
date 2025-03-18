---

# Project Charter

## Project Details
- **Name:** Single-Cell-RNA-seq-Dimensionality-Reduction-and-Clustering  
- **Lead:** Mark Endicott
- **Sponser:** Casey Detrio
- **Biotech Advisor:** Steven Ouellette PhD
- **Start Date:** 12/22/2024  
- **Expected End Date:** TBD  

## Project Objectives  
### 1. Develop an Autoencoder-Based Aging Clock  
- Implement an autoencoder model trained on transcriptomic data from the `ad_worm_aging.h5ad` dataset.  
   
### 2. Compare Dimensionality Reduction Techniques  
- Evaluate autoencoder-based embeddings alongside PCA, t-SNE, Diffusion Maps, and NMF-based embeddings.  
- Compute clustering performance using silhouette scores, Calinski-Harabasz scores, and Davies-Bouldin scores.  

### 3. Test Generalizability to Other Datasets  
- Apply the autoencoder to a different C. elegans dataset (Gao et al., 2024) to compare performance and generalizability.  

### 4. Analyze Aging-Related Gene Representations  
- Identify which features in the latent space of the autoencoder correlate with known aging-related genes and pathways.  
- Assess whether other methods (e.g., PCA, NMF) capture similar biological signals.  

### 5. Disseminate Findings  
- Document findings in code notebooks, slides, and a GitHub repository 

## Scope  

### In Scope  
- Development and training of a deep learning autoencoder for transcriptomic aging prediction.  
- Comparison of dimensionality reduction methods (Autoencoder, PCA, t-SNE, Diffusion Maps, NMF).    
- Analysis of the biological interpretability of dimensionality reduction results.  
- Publishing results via GitHub, blog posts, and presentations.  

## Deliverables  
- **Python Code:** Autoencoder model, dimensionality reduction scripts, and evaluation scripts.  
- **Data Analysis Notebooks:** Jupyter Notebook with code, results, and visualizations.  
- **GitHub Repository:** Organized repository with code, data, and documentation.  
- **Final Report:** A concise write-up summarizing methodology, findings, and implications.  
- **Visualizations:** UMAP projections, clustering results, aging clock performance plots, and gene expression trends.  
- **Evaluation Metrics:** Silhouette scores, Calinski-Harabasz scores, Davies-Bouldin scores.  
- **Media Content:** Blog posts and presentations to share key insights.  

## Resources  

### Hardware  
- Personal laptop capable of running ML models efficiently.  

### Software/Tools  
- **Programming:** Python, Command-Line  
- **Libraries:** Scanpy, PyTorch, NumPy, Seaborn, Scikit-learn  
- **Development Environment:** Anaconda, JupyterLab  
- **Project Management & Communication:** Notion, Telegram  

### Documentation & Reporting  
- GitHub repository  
- Final project write-up

---


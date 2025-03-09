# Project Charter

## Project Details
- **Name:** Single-Cell-RNA-seq-Dimensionality-Reduction-and-Clustering  
- **Lead:** Mark Endicott  
- **Start Date:** 12/22/2024  
- **Expected End Date:** TBD  

## Project Objectives  
1. **Develop an Autoencoder-Based Aging Clock**  
   - Implement an autoencoder model trained on transcriptomic data from the Roux et al., 2023 dataset.  
   
2. **Assess Autoencoder Performance**  
   - Evaluate the model’s ability to predict aging-related transcriptomic changes using standard metrics (e.g., MAE, R²).  

3. **Test Generalizability to Other Datasets**  
   - Apply the autoencoder to a different C. elegans dataset (Gao et al., 2024) to compare performance and generalizability.  

4. **Analyze Aging-Related Gene Representations**  
   - Identify which features in the latent space of the autoencoder correlate with known aging-related genes and pathways.  

5. **Disseminate Findings**  
   - Document findings in code notebooks, a GitHub repository, and blog posts.  

## Scope  

### In Scope  
- Development and training of a deep learning autoencoder for transcriptomic aging prediction.  
- Model evaluation and benchmarking on multiple datasets.  
- Analysis of the biological interpretability of autoencoder representations.  
- Publishing results via GitHub, blog posts, and presentations.  

### Out of Scope  
- Experimental biological validation of predictions.  
- Alternative model architectures beyond basic autoencoders.  
- Development of a user-friendly interface or web app.  

## Deliverables  
- **Python Code:** Autoencoder model and evaluation scripts.  
- **Data Analysis Notebooks:** Jupyter Notebooks with code, results, and visualizations.  
- **GitHub Repository:** Organized repository with code, data, and documentation.  
- **Final Report:** A concise write-up summarizing methodology, findings, and implications.  
- **Visualizations:** UMAP projections, aging clock performance plots, and gene expression trends.  
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


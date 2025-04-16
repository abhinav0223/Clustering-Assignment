# Clustering-Assignment

# Wine Dataset Clustering Analysis

This project performs Clustering on the UCI Wine dataset using different preprocessing techniques and clustering algorithms. The performance is evaluated using standard clustering metrics.

# Dataset
Source: UCI Machine Learning Repository

Features: 13 numerical features describing the chemical properties of wine

Target: Type of wine (used only for reference, not in Clustering)

 # Clustering Techniques
 K-Means Clustering,
 Hierarchical Clustering,
 Mean Shift Clustering

 # Preprocessing Techniques
Raw (no preprocessing),
Normalization (StandardScaler),
Transformation (PowerTransformer),
PCA (2 components),
Normalization + Transformation,
Normalization + Transformation + PCA

# Evaluation Metrics
Silhouette Score (higher is better),
Calinski-Harabasz Index (higher is better),
Davies-Bouldin Score (lower is better)

 # Results Summary
Results were computed for each combination of preprocessing and clustering algorithms with 3, 4, and 5 clusters. Mean Shift estimates clusters automatically.
Results are saved in wine_clustering_results.csv

 # Observations
Best Silhouette Scores were generally observed using Raw or Normalized data with KMeans.
PCA reduced performance slightly but made data easier to visualize.
Mean Shift automatically determined cluster count, with varying success.
Normalization + Transformation improved performance for some methods (esp. Hierarchical).

 # How to Run
Run the notebook or Python script on any Python environment or Google Colab.

 # Conclusion
Clustering performance varies based on preprocessing. KMeans and Hierarchical Clustering worked best with normalized or raw features. PCA helps visualization but might reduce performance slightly.

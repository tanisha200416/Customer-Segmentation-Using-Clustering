# Customer Segmentation Using Clustering

## Project Overview
This project focuses on customer segmentation using Unsupervised Machine Learning techniques. The objective is to group customers based on their demographic and financial characteristics to identify meaningful customer segments.

## Algorithms Used
Three clustering algorithms were implemented:

1. **K-Means Clustering** – Groups customers into clusters based on similarity.
2. **Hierarchical Clustering** – Creates clusters using a hierarchical tree structure.
3. **DBSCAN** – Identifies clusters based on data density and detects noise points.

## Dataset
The project uses a customer segmentation dataset containing features such as:
- Sex
- Marital Status
- Age
- Education
- Income
- Occupation
- Settlement Size

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- VS Code / Jupyter Notebook

## Model Evaluation

The clustering models were evaluated using Silhouette Score and Davies-Bouldin Score.

| Algorithm | Number of Clusters | Silhouette Score | Davies-Bouldin Score |
|---|---:|---:|---:|
| K-Means | 3 | 0.2423 | 1.5139 |
| Hierarchical | 3 | 0.1635 | 1.8766 |
| DBSCAN | 5 | 0.0861 | 1.1509 |

**Observation:** K-Means achieved the highest Silhouette Score, while DBSCAN achieved the lowest Davies-Bouldin Score. Each metric provides a different perspective on clustering quality.

*Note: DBSCAN evaluation excludes noise points.*

## Project Structure
- `kmeans.ipynb` – K-Means implementation
- `hierarchical.ipynb` – Hierarchical clustering implementation
- `dbscan.ipynb` – DBSCAN implementation
- `model_comparison.ipynb` – Model evaluation and comparison
- `segmentation data.csv` – Dataset
- CSV result files – Clustering outputs and model comparison

## How to Run
1. Clone this repository.
2. Install the required libraries:
   `pip install pandas numpy matplotlib seaborn scikit-learn scipy`
3. Open the project in VS Code or Jupyter Notebook.
4. Run the notebooks individually.

## Conclusion
This project explores three unsupervised learning algorithms for customer segmentation and compares their clustering performance using evaluation metrics.
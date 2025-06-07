# Clustering with K-Means

This project demonstrates **unsupervised learning** using the **K-Means Clustering** algorithm on the Mall Customer Segmentation dataset.

## 📌 Objective
To perform customer segmentation using clustering techniques and understand how K-Means works, including optimal cluster selection and evaluation.

## 📂 Dataset
**Mall Customer Segmentation**  
[Download Link (Kaggle)](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

## 🛠️ Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib & Seaborn

## 📊 Workflow
1. Load and explore the dataset
2. Feature scaling using `StandardScaler`
3. Apply the **Elbow Method** to find optimal `k`
4. Fit **K-Means** and assign cluster labels
5. Visualize clusters
6. Evaluate clustering using **Silhouette Score**
7. Optional: PCA for 2D visualization

## 📈 Key Outputs
- Elbow curve to choose number of clusters
- Cluster visualization on `Annual Income vs Spending Score`
- Silhouette Score for cluster quality
- PCA-based visualization (optional)

## 🔍 Results
- Optimal number of clusters: **5**
- Achieved **Silhouette Score**: ~0.55 (varies slightly per run)

## 🧠 Learnings
- How unsupervised learning (K-Means) groups similar data points
- Cluster evaluation methods like **inertia** and **Silhouette Score**
- Importance of feature scaling and dimensionality reduction

## ✅ How to Run
1. Clone the repo
2. Open the notebook in Jupyter or Google Colab
3. Install dependencies (`pip install -r requirements.txt` if needed)
4. Run all cells


## Submission
Submitted as part of the AI & ML Internship - Task 8.

---

### Author
**Vishwajeet Kumar**  
BS in Data Science and Applications @ IIT Madras  
BTech CSE @ LNJPIT Chapra, BEU Patna
> GitHub: [github.com/wivk-tech](https://github.com/wivk-tech)

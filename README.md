# 🌸 Iris Flower Clustering Project

## 📌 Project Overview
This project performs **Unsupervised Machine Learning** using the K-Means Clustering algorithm on the Iris Flower dataset obtained from Kaggle.

The main objective is to group Iris flowers into three clusters based on their physical measurements and visualize the results using scatter plots and Principal Component Analysis (PCA).

## 🎯 Objectives
- Perform K-Means Clustering with K=3.
- Apply the Elbow Method to determine the optimal number of clusters.
- Perform feature scaling using StandardScaler.
- Reduce dataset dimensions using PCA.
- Visualize the predicted clusters.
- Compare predicted clusters with actual species labels.
- Save and load trained models using Joblib.

## 📂 Dataset
**Source:** [Kaggle – Iris Species Dataset](https://www.kaggle.com/datasets/uciml/iris)

The dataset contains 150 flower records and 6 columns.

### Features Used:
- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

### Target Species:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

## 🛠️ Technologies Used
- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## ⚙️ Project Workflow

1. Imported required Python libraries.
2. Loaded the Iris dataset from Kaggle.
3. Performed data exploration and preprocessing.
4. Checked missing values and dataset information.
5. Selected four numerical features for clustering.
6. Applied feature scaling using StandardScaler.
7. Used the Elbow Method to analyze the optimal K value.
8. Applied K-Means Clustering with K=3.
9. Visualized the predicted clusters using scatter plots.
10. Compared predicted clusters with actual species labels using a confusion matrix.
11. Applied PCA to reduce four dimensions into two principal components.
12. Saved and loaded trained models using Joblib.

## 📊 Algorithms Implemented

### 1. K-Means Clustering
K-Means is an unsupervised learning algorithm that groups similar data points into clusters based on distance.

In this project, K=3 is used to create three clusters.

### 2. Elbow Method
The Elbow Method helps determine a suitable number of clusters by analyzing Within-Cluster Sum of Squares (WCSS).

### 3. Principal Component Analysis (PCA)
PCA is a dimensionality reduction technique that transforms four original features into two principal components for visualization.

### 4. Feature Scaling
StandardScaler is used to normalize the feature values before applying K-Means.

## 📈 Results
- Successfully loaded 150 Iris flower records.
- No missing values were found.
- Applied K-Means clustering with three clusters.
- Visualized the predicted clusters.
- Compared actual species labels with predicted clusters.
- Reduced dataset dimensions from 4 to 2 using PCA.
- Successfully saved and loaded the trained models.

**Note:** K-Means cluster numbers do not directly correspond to actual species labels. Cluster labels are assigned independently by the algorithm.

## 💾 Model Saving
The trained models were saved using Joblib:

- `kmeans_iris_model.pkl`
- `scaler.pkl`
- `pca_model.pkl`

## 📁 Project Structure

```text
Iris-Flower-Clustering/
│
├── Iris.csv
├── iris_clustering.ipynb
├── kmeans_iris_model.pkl
├── scaler.pkl
├── pca_model.pkl
├── requirements.txt
└── README.md
```

## ▶️ How to Run the Project

**Step 1: Clone the repository**

```bash
git clone https://github.com/sanikagundakar9/Iris-Flower-Clustering.git
```

**Step 2: Open the project folder**

```bash
cd Iris-Flower-Clustering
```

**Step 3: Install dependencies**

```bash
pip install -r requirements.txt
```

**Step 4: Open Jupyter Notebook**

```bash
jupyter notebook
```

**Step 5:** Open `iris_clustering.ipynb` and run all cells.

## 🏆 Skills Gained
- Unsupervised Machine Learning
- K-Means Clustering
- Dimensionality Reduction
- Principal Component Analysis
- Data Visualization
- Feature Scaling
- Model Evaluation
- Model Saving and Loading

## 👩‍💻 Author
**Sanika Gundakar**

Machine Learning & AI Internship – Week 3

GitHub: [sanikagundakar9](https://github.com/sanikagundakar9)

---

⭐ **This project was completed as part of the Machine Learning & AI Internship – Week 3 assignment.**
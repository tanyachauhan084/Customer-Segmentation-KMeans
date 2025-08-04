# 🧠 Customer Segmentation using K-Means Clustering

This project applies **K-Means Clustering**, an unsupervised machine learning algorithm, to segment customers based on their purchasing behavior. It helps businesses better understand customer groups and tailor their marketing strategies accordingly.

---

## 📊 Problem Statement

Businesses often deal with large customer bases with diverse behaviors. By applying clustering algorithms, we aim to:

- Group customers into segments based on purchasing patterns
- Identify high-value customer groups
- Help businesses target the right audience for specific campaigns

---

## 🛠️ Tech Stack & Libraries

- **Language:** Python  
- **Libraries:**
  - `pandas` – data manipulation
  - `matplotlib`, `seaborn` – data visualization
  - `scikit-learn` – machine learning (KMeans)
  - `numpy` – numerical computations

---

## 🧮 Algorithm Used

**K-Means Clustering**  
- Unsupervised learning algorithm
- Groups data into `k` clusters based on feature similarity
- Uses Euclidean distance to assign clusters

---

## 📁 Dataset

- **Source:** [e.g., Mall Customers Dataset - Kaggle](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Features Used:**
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## 📈 Exploratory Data Analysis (EDA)

- Visualized distributions (Age, Income, Spending Score)
- Checked correlations
- Identified ideal number of clusters using the **Elbow Method**

---

## 🔍 How K-Means Was Applied

1. **Preprocessing**: Selected relevant features (Annual Income, Spending Score)
2. **Finding optimal clusters**: Used the Elbow method to determine best value of `k`
3. **Modeling**: Applied KMeans and trained the model
4. **Visualization**: Plotted the clusters in 2D to see customer segmentation

---

## 📌 Results

- Optimal number of clusters: **5**
- Segmented customers into groups like:
  - High Income, High Spend
  - Low Income, Low Spend
  - High Income, Low Spend
  - etc.

---

## 📊 Visuals

- Elbow Curve for finding `k`
- Scatter plot of clusters
- Cluster centroids

---


## 🚀 How to Run

1. Clone the repository
git clone https://github.com/tanyachauhan084/Customer-Segmentation-KMeans.git

2. Install dependencies
pip install -r requirements.txt

3. Run the notebook
Jupyter Notebook _Customer_Segmentation_.ipynb


## 👩‍💻 Author
Tanya Chauhan
📧 tanyachauhan084@gmail.com
🌐 LinkedIn [https://www.linkedin.com/in/tanya-chauhan-99a5aa355/]


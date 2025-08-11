
# 🛍️ Customer Segmentation using K-means Clustering

## 📌 Overview

This project implements a **K-means clustering algorithm** to segment customers of a retail store based on their purchase history.
The **Mall Customer Dataset** is used to identify distinct customer groups, which can help in targeted marketing and personalized recommendations.

---

## 📂 Dataset

The dataset contains the following columns:

* `CustomerID` – Unique ID assigned to each customer.
* `Gender` – Male/Female.
* `Age` – Age of the customer.
* `Annual Income (k$)` – Annual income of the customer in thousands of dollars.
* `Spending Score (1-100)` – Spending score assigned by the mall based on customer behavior.

---

## ⚙️ Installation

Install the required dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

---

## 🚀 Usage

1. **Clone the repository** or download the project files.
2. Place the dataset file (e.g., `Mall_Customers.csv`) in the project folder.
3. Run the script:

```bash
python customer_segmentation.py
```

---

## 📊 Model Details

The project uses **K-means clustering** from `scikit-learn`:

```python
from sklearn.cluster import KMeans
```

**Steps:**

1. Load and explore the dataset using **Pandas**.
2. Select relevant features (e.g., `Annual Income`, `Spending Score`).
3. Use the **Elbow Method** to find the optimal number of clusters.
4. Apply **K-means clustering**.
5. Visualize clusters using **Matplotlib** and **Seaborn**.

---

## 📈 Example Output

* Elbow Method plot showing optimal `k`.
* Scatter plot visualizing customer clusters.

Example:

```
Optimal number of clusters: 5
Cluster Centers:
[[40.0, 60.0], [20.0, 20.0], [60.0, 20.0], [25.0, 80.0], [80.0, 80.0]]
```

---

## 📌 Future Improvements

* Include **Age** as an additional clustering feature.
* Try **Hierarchical Clustering** for comparison.
* Deploy an **interactive dashboard** to view customer segments.

---

## 🖋 Author

**Nirmal Chaturvedi**

---

If you want, I can now **write the Python code** for K-means on the Mall Customer Dataset and run it to produce actual cluster visualizations.
Do you want me to prepare that next?

# Customer Personality Analysis & Segmentation 📊

### 🎯 Project Overview
This project uses unsupervised machine learning to perform **Customer Personality Analysis**. By segmenting a company's customer base, we can identify hidden patterns in purchasing behavior, demographics, and campaign responses to drive high-ROI marketing strategies.

### 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Scikit-Learn, Yellowbrick, Seaborn, Matplotlib.
* **Algorithms:** K-Means Clustering, Agglomerative Clustering, PCA (Dimensionality Reduction).

### 🚀 Key Features & Workflow
1.  **Data Cleaning:** Handled missing values and removed outliers in `Income` and `Age`.
2.  **Feature Engineering:** Created high-impact variables like `Total_Spent`, `Is_Parent`, and `Family_Size` to better capture household dynamics.
3.  **Dimensionality Reduction:** Used **PCA** to condense 20+ features into 3 principal components, retaining maximum variance while enabling 3D visualization.
4.  **Optimal Clustering:** Leveraged the **Elbow Method** (KElbowVisualizer) to mathematically determine that 4 clusters provided the most stable segmentation.
5.  **Visualization:** Built 3D scatter plots to validate cluster separation and profile distribution.

### 📈 Results
The model successfully identified four distinct groups:
* **Stars:** High-income, high-spending "VIP" clients.
* **Budget Shoppers:** Price-sensitive customers focused on deals.
* **Leisurely:** Older customers with high luxury/wine spending.
* **Families:** Large households prioritizing essential purchases.

---
*Developed as part of a Data Science Portfolio. Data sourced from Kaggle/Marketing Campaign dataset.*

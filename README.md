# Customer Personality Analysis & Segmentation 📊

### 🎯 Project Overview
This project uses unsupervised machine learning to perform **Customer Personality Analysis**. By segmenting a company's customer base, we can identify hidden patterns in purchasing behavior, demographics, and campaign responses to drive high-ROI marketing strategies.

### 📈 Key Visualizations

#### 1. Optimal Cluster Selection (The Elbow Method)
Before clustering, I used the Distortion Score Elbow boundary to determine the ideal number of segments. The "elbow" point indicates where adding more clusters no longer significantly improves the model.
<img width="789" height="516" alt="cluster_formation" src="https://github.com/user-attachments/assets/bd2591b3-7681-4b0f-bf68-39af77659d5a" />


#### 2. Dimensionality Reduction (PCA)
To handle the "curse of dimensionality," I used Principal Component Analysis to reduce 20+ features into 3 principal components. This allowed for the following 3D spatial representation of our customer segments.
<img width="645" height="658" alt="3d_reduced_dim" src="https://github.com/user-attachments/assets/07a45e1a-7a4e-4abe-8f3b-f8fad6be43aa" />


#### 3. Segment Profiling
After clustering, I analyzed the distribution of spending across different groups to define our four personas: Stars, Budget, Families, and Leisurely.
<img width="1324" height="1228" alt="feature_plot" src="https://github.com/user-attachments/assets/93ae4de5-a7dc-475a-b680-72e91cb30420" />


### 🛠️ Tech Stack
* **Language:** Python 3.119
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

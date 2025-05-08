# 🔍 EV Market Segmentation Using K-Means Clustering

## 📁 Project Title
**Market Segmentation Analysis of Indian Electric Vehicle (EV) Dataset**

## 🧠 Objective
This project aims to analyze and segment electric vehicles in India using machine learning techniques. By clustering EVs based on key attributes, we identify patterns in pricing, performance, and environmental efficiency that can assist manufacturers and startups in targeting the right market segments.

---

## 📊 Dataset
**File**: `indian_vehicle_dataset_jahaganapathi_s.csv`  
**Source**: Custom dataset curated to include various vehicle types, manufacturers, and technical specs.

### Key Features Used for Clustering:
- `Units_Sold`  
- `Price`  
- `Mileage_kmpl`  
- `CO2_Emission_g_km`  

Only vehicles marked as **Electric (`EV_Status == 'Yes'`)** are included in the clustering analysis.

---

## 🛠️ Technologies Used
- Python 🐍
- Pandas & NumPy (Data Manipulation)
- Matplotlib & Seaborn (Visualization)
- Scikit-learn (ML & Preprocessing)
- PCA (Dimensionality Reduction)

---

## ⚙️ Workflow

### 1. Data Preprocessing
- Removed duplicates
- Filtered for EVs only
- Cleaned null values from key columns
- Standardized numeric features using `StandardScaler`

### 2. K-Means Clustering
- Determined the optimal number of clusters using the **Elbow Method**
- Applied K-Means clustering (`k=3`)
- Added cluster labels to the dataset

### 3. Visualizations
- 📈 **Elbow Curve** for optimal k
- 🧩 **Pairplot** of clustered features
- 🧊 **Correlation Heatmap**
- 🏭 **Cluster Distribution by Manufacturer**
- 🌀 **2D PCA Scatter Plot** for cluster visualization

---

## 💡 Key Insights
- Cluster 0: Budget EVs with moderate performance
- Cluster 1: High-efficiency EVs with better mileage and lower emissions
- Cluster 2: Niche/outlier EVs with unique characteristics

These clusters help identify gaps and opportunities in the EV market and guide manufacturers in targeting the right segments.

---


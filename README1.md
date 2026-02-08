# 🌍 Air Quality Clustering using K-Means

## 📌 Project Title
**Clustering Cities Based on Air Pollution using K-Means Algorithm**

---

## 🎯 Aim
To apply the K-Means clustering algorithm on the Global Air Pollution Dataset to group cities based on their air quality levels (AQI and PM2.5), and analyze pollution patterns.

---

## 🎯 Objectives
- Understand unsupervised learning using K-Means  
- Preprocess real-world air pollution data  
- Identify hidden groups of cities based on pollution similarity  
- Visualize clusters before and after applying K-Means  
- Interpret pollution-based city clusters  

---

## 📊 Dataset
**Global Air Pollution Dataset (Kaggle)**  

**Features used:**
- AQI Value  
- PM2.5 AQI Value  
- PM10 AQI Value  
- NO2 AQI Value  
- SO2 AQI Value  
- CO AQI Value  
- O3 AQI Value  

**Removed columns:**
- City, Country, non-numeric fields  

---

## 🧪 Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## ⚙️ Methodology / Steps
1. Import the dataset  
2. Handle missing values (drop or fill)  
3. Select numeric pollution features  
4. Scale the data using `StandardScaler`  
5. Find optimal K using Elbow Method  
6. Apply K-Means clustering  
7. Add cluster labels to the dataset  
8. Visualize before & after clustering  
9. Generate cluster summary table  
10. Interpret the results  

---

## 📈 Visualizations
- **Before Clustering:** AQI vs PM2.5 (single color)  
- **After Clustering:** AQI vs PM2.5 (colored by cluster)  
- Highlight top polluted cities  
- Cluster summary table  

---

## 🧠 Learning Outcomes
- How unsupervised learning works  
- How K-Means forms clusters based on distance  
- The importance of feature scaling  
- How to choose optimal number of clusters  
- How to visualize and interpret clustering results  
- How real-world data can be grouped to find hidden patterns  

---

## ✅ Conclusion
K-Means successfully grouped cities into pollution-based clusters such as **low, moderate, and high polluted regions**.  
This helps in understanding air quality patterns and identifying critical pollution zones.

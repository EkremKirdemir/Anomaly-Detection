# 🧠 Anomaly Detection in Raw Material Purchases – Torun Metal

This project aims to detect pricing anomalies in the purchase records of CW614N/CW617N raw materials over a 5-year period using Python and unsupervised learning techniques.

## 📊 Project Description

Procurement data often includes inconsistencies and outliers that can lead to significant financial losses. This project analyzes historical purchase data and market prices to automatically identify overpriced transactions using:

- **Z-Score** (Statistical outlier detection)
- **IQR (Interquartile Range)** based filtering
- **DBSCAN** (Density-Based Spatial Clustering of Applications with Noise)

A **majority voting system** is implemented to improve robustness by combining the outputs of the three methods. Anomalies are only flagged if at least two techniques agree.

---

## 📁 Key Features

- 📈 Visualizes anomalies in scatter and time series plots
- 📂 Exports results into Excel sheets (with `tum_anomaliler` and `overpriced_anomaliler`)
- 🧾 Automatically generates a well-structured PDF report with all findings and charts
- 🧮 Calculates total loss, quantity, and anomaly statistics

---

## 📁 Files

- `Untitled.ipynb`: Main notebook including all anomaly detection logic and visualizations.
- `anomaliler.xlsx`: Output file containing detected anomalies.
- `overpriced_anomali_raporu.pdf`: Final report in PDF format including plots and summaries.

---

## 📌 Sample Output

**Total Loss Identified:** €78,776  
**Average Price Ratio (Overpriced):** 1.45  
**Number of Overpriced Anomalies:** 17  

---

## ⚙️ Technologies Used

- Python 3.x
- NumPy, Pandas
- Matplotlib
- scikit-learn
- FPDF
- OpenPyXL

---

## 🧑‍💻 Author

**Ekrem Kırdemir**  
*Software Developer Intern @ Torun Metal A.Ş.*

---

## 📄 License

This project is for academic and demonstrative purposes only.

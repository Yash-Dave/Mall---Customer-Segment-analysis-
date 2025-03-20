# **Customer Segmentation for E-Commerce using Clustering**

## **📌 Project Overview**
This project performs **customer segmentation** using clustering techniques on e-commerce data. The goal is to group customers based on **purchasing behavior, demographics, and spending patterns** to help businesses optimize **marketing strategies, customer engagement, and retention**.

We apply **K-Means and DBSCAN clustering algorithms** to segment customers and visualize the results using **Tableau** for better business insights.

---

## **🔹 Dataset Description**
This project uses a public dataset, `Mall_Customers.csv`, and enhances it with **synthetic customer data** generated using bootstrapping + Gaussian noise. The dataset contains:

| Column Name | Description |
|-------------|------------|
| `Gender` | Customer gender (Male/Female) |
| `Age` | Customer age in years |
| `Annual Income (k$)` | Annual income in thousands of dollars |
| `Spending Score (1-100)` | Score representing spending habits |
| `KMeans_Cluster` | Cluster labels assigned by K-Means |
| `DBSCAN_Cluster` | Cluster labels assigned by DBSCAN |

---

## **📊 Data Preprocessing & Feature Engineering**
1. **Data Cleaning**: Handling missing values and outliers.
2. **Feature Scaling**: Using `StandardScaler` to normalize data.
3. **Dimensionality Reduction**: Applying **PCA** for visualization.
4. **Synthetic Data Generation**: Using **bootstrapping with noise** for enhanced training.

---

## **🛠️ Clustering Techniques Used**
1. **K-Means Clustering**:
   - Elbow method to find the optimal `k`
   - Segments customers into distinct groups
   - Visualized in Tableau and PCA plots

2. **DBSCAN (Density-Based Clustering)**:
   - Finds clusters of arbitrary shapes
   - Detects outliers and noise in the data
   - Requires fine-tuned `eps` and `min_samples` parameters

---

## **📈 Visualizations & Insights**
### **Tableau Dashboard Includes:**
✔ **Scatter Plot** (Income vs. Spending Score) - Color-coded clusters  
✔ **Bar Chart** (Cluster-wise customer distribution)  
✔ **Box Plots** (Spending habits by Age & Gender)  
✔ **Filters & Interactive Elements** (Dynamic segment analysis)  

📌 **Key Business Insights:**
- High-income, low-spending customers → Potential for premium services.
- Young customers with high spending → Target for loyalty programs.
- Older customers with moderate spending → Engagement strategies needed.

---

## **🚀 Installation & Setup**
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/Yash-Dave/Mall-Customer-Segment-analysis.git
```

### **2️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **3️⃣ Run the Jupyter Notebook**
```bash
jupyter notebook notebooks/customer_segmentation.ipynb
```
---

## **📌 Key Python Libraries Used**
- `pandas` → Data manipulation
- `numpy` → Numerical operations
- `matplotlib & seaborn` → Data visualization
- `sklearn` → Clustering & PCA

---

## **📜 Project Results & Findings**
✔ **Identified meaningful customer segments** based on income & spending behavior.  
✔ **Improved engagement strategies** through cluster-based insights.  
✔ **Enhanced interpretability** with an interactive Tableau dashboard.  
✔ **Demonstrated synthetic data generation skills** by extending a public dataset.  

---

## **🔗 Additional Resources**
- [K-Means Clustering Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)
- [DBSCAN Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html)
- [Tableau Public](https://public.tableau.com/)

---

## **🤝 Contributing**
Pull requests are welcome! For major changes, please open an issue first to discuss proposed modifications.

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature-name`.
3. Commit changes: `git commit -m 'Add feature-name'`.
4. Push the branch: `git push origin feature-name`.
5. Submit a pull request.

---

## **📞 Contact & Feedback**
📧 Email: `your-email@example.com`  
🔗 LinkedIn: [Yash Dave](https://www.linkedin.com/in/yashrdave/)  
🐙 GitHub: [Your GitHub Profile](https://github.com/Yash-Dave)  

⭐ **If you find this project helpful, please consider giving it a star on GitHub!** ⭐


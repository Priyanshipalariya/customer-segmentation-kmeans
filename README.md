 **Customer Segmentation Using K-Means Clustering**

This project applies K-Means clustering to segment mall customers based on their Annual Income and Spending Score. It helps identify distinct customer groups for targeted marketing strategies.


**Overview**

**Objective:**  
Group customers into distinct segments to help businesses understand consumer behavior and tailor their marketing accordingly.


**Dataset Used:**  
Mall Customers Dataset (Kaggle)(https://www.kaggle.com/datasets/shwetabh123/mall-customers?resource=download)


**Technologies & Libraries**
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook



**Steps Followed**

1. **Data Preprocessing:** Loaded and explored the dataset.
2. **Feature Selection:** Focused on 'Annual Income' and 'Spending Score'.
3. **Standardization:** Scaled data using `StandardScaler`.
4. **Elbow Method:** Determined optimal number of clusters (`k=5`).
5. **Modeling:** Applied K-Means clustering.
6. **Visualization:** Used scatter plots to visualize customer segments.
7. **Insight Generation:** Interpreted clusters and their characteristics.



## Visual Output

![Customer Segments](assets/customer_segments.png)  


**How to Run**
1. Clone the repo or download the files:
           `git clone https://github.com/Priyanshipalariya/customer-segmentation-kmeans.git`

2. Open customer_segmentation.ipynb in Jupyter Notebook or Google Colab.

3.Install required libraries if not already:
           `pip install pandas numpy matplotlib seaborn scikit-learn`

4.Run all cells in order.

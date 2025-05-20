# Customer_transaction_behaviour_analysis

To analyze transactional behavior patterns of users on a synthetic dataset mimicking real-world payment platform activity, and extract insights for **customer segmentation** and **fraud detection** using data analytics and visualization techniques.

## 🛠️ Tools & Technologies  
- **Programming Languages:** Python (Pandas, NumPy, Matplotlib, Seaborn)  
- **Data Querying:** SQL (MySQL/PostgreSQL)  
- **Visualization:** Tableau  
- **Clustering Algorithm:** K-Means  
- **Notebook:** Jupyter

## 📂 Dataset  
- **Type:** Synthetic transaction data  
- **Size:** 1 Million+ records  
- **Fields Included:** `User_ID`, `Transaction_ID`, `Timestamp`, `Location`, `Transaction_Amount`, `Category`, `Device_Type`, `Status`  

## 🔍 Key Steps  

1. **Data Cleaning & Preprocessing**  
   - Removed nulls, corrected timestamps, normalized transaction amounts.  
   - Feature engineering: Added `Time of Day`, `Day of Week`, and `Spending Score`.

2. **Behavioral Clustering (K-Means)**  
   - Segmented users into behavioral clusters:  
     - **Budget Users**, **Premium Spenders**, **Frequent Micro-Users**, etc.  
   - Used Elbow Method to optimize number of clusters.  

3. **Data Visualization (Tableau Dashboard)**  
   - Built interactive dashboards to view:  
     - Regional heatmaps of high-value transactions  
     - Time-based spending behavior  
     - Category-wise distribution (e.g., Food, Utilities, Subscriptions)

4. **Fraud Insight Potential**  
   - Flagged outlier clusters with unusually high frequency or values in odd hours/locations.  
   - Proposed rules-based system for anomaly detection.

## 📈 Outcomes  
- Identified **4 unique customer personas** based on spending patterns.  
- Built a dashboard enabling product managers to view behavioral trends.  
- Provided groundwork for implementing **fraud detection** and **personalized rewards**.

## 🚀 How to Run  
1. Clone the repo  
2. Run the Jupyter Notebook `analysis.ipynb`  
3. View the Tableau dashboard (`Customer_Behavior.twbx`)

## 🤝 Contributions & Future Work  
- Expand with DBSCAN for better anomaly detection  
- Add LTV prediction model for each user segment

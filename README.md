# **Mall Customer Segmentation using K-Means Clustering**
  
## 📌 **Project Overview**
Understanding customer behavior is essential for **targeted marketing and business growth**. This project applies **K-Means Clustering** to segment customers based on **annual income, spending score, and age**. By identifying **distinct customer groups**, businesses can design **personalized marketing strategies**, optimize **customer engagement**, and improve **revenue generation**.  

---

## 🎯 **Why This Project?**
- Customer segmentation is a **critical component** of data-driven decision-making for businesses.  
- Helps businesses **identify high-value customers** and tailor marketing strategies accordingly.  
- Enables companies to **increase customer retention, optimize promotions, and drive sales growth**.  

---

## 🔥 **Industry Applications**
1. **Targeted Marketing & Personalized Promotions**  
   - Identifies high-value customers for **exclusive discounts, rewards, and offers**.  
   - Engages price-sensitive customers with **budget-friendly promotions**.  

2. **Optimized Store Layout & Inventory Management**  
   - **Improves product placement** based on customer segmentation.  
   - Helps **predict product demand** to prevent overstock and shortages.  

3. **Enhancing Customer Experience & Retention**  
   - Retains premium customers through **VIP programs & loyalty incentives**.  
   - Re-engages **low-spending customers** with personalized marketing strategies.  

---

## 🚀 **Technologies Used**
- **Google Colab** – For coding, data analysis, and visualization.  
- **Overleaf** – For generating professional PDF reports using LaTeX.  

---

## 📚 **Libraries Used**
- **pandas** – For data manipulation.  
- **numpy** – For numerical computations.  
- **matplotlib & seaborn** – For data visualization.  
- **scikit-learn** – For implementing the K-Means clustering algorithm.  

---

## 📊 **Methodology**
1. **Data Preprocessing**  
   - Load and clean customer data.  
   - Handle missing values and perform exploratory data analysis (EDA).  

2. **Feature Selection**  
   - Consider **Annual Income, Spending Score, and Age** for clustering.  

3. **Clustering Using K-Means**  
   - Determine the **optimal number of clusters** using the **Elbow Method**.  
   - Apply **K-Means clustering** to segment customers.  

4. **Result Visualization**  
   - **2D Scatter Plot**: Customer segmentation based on **Annual Income & Spending Score**.  
   - **3D Visualization**: Customer segmentation based on **Age, Income & Spending Score**.  

---

## 📈 **Data Visualizations & Observations**
### **1. Distribution of Annual Income**
📌 *Observation:*  
- The distribution of annual income is **right-skewed**, meaning fewer customers have extremely high incomes.  
- Most customers earn between **40k$ and 80k$**, with a peak around **60k$**, indicating a middle-income customer base.  

📷 **Screenshot Placeholder:**  
![Annual Income Distribution](https://github.com/user-attachments/assets/9a3f8ee8-877e-401b-9a30-e668ea22ec6d)

---

### **2. Distribution of Age**
📌 *Observation:*  
- The majority of customers fall between **25 to 40 years old**, with the peak around **30 years**, suggesting a younger customer base.  
- Very few customers are aged **above 60**, indicating that businesses targeting senior citizens might need a different approach.  

📷 **Screenshot Placeholder:**  
![Age Distribution](https://github.com/user-attachments/assets/6c5465d4-f9b9-477a-93fa-1a414113addc)

---

### **3. Distribution of Spending Score**
📌 *Observation:*  
- The spending scores range from **0 to 100**, with most customers scoring between **40 and 60**, indicating a mix of moderate spenders.  
- The distribution is slightly **bimodal**, meaning there are two dominant spending groups—moderate spenders and high spenders.  

📷 **Screenshot Placeholder:**  
![Spending Score Distribution](https://github.com/user-attachments/assets/83e4308b-0824-40b2-bfb8-b06cf3947b6d)

---

### **4. Elbow Method (WCSS vs K for 2D Clustering)**
📌 *Observation:*  
- The **elbow point appears at K=5**, meaning five clusters provide an optimal segmentation of customers.  

📷 **Screenshot Placeholder:**  
![Elbow Method 2D](https://github.com/user-attachments/assets/b2beafd4-a256-47f5-b7b2-81fb1fb767ae)

---

### **5. 2D Customer Segmentation (Annual Income vs Spending Score)**
📌 *Observation:*  
- The scatter plot reveals five well-defined clusters, separating customers based on income and spending patterns.  
- **High-income, high-spending customers (black cluster)** are premium buyers who may respond well to luxury and exclusive offers.  

📷 **Screenshot Placeholder:**  
![2D Segmentation](https://github.com/user-attachments/assets/102f197b-ae30-4a2e-9533-be6963d25d00)

---

### **6. Elbow Method (WCSS vs K for 3D Clustering)**
📌 *Observation:*  
- The **optimal number of clusters remains at K=5**, even when age is introduced as an additional dimension.  

📷 **Screenshot Placeholder:**  
![Elbow Method 3D](https://github.com/user-attachments/assets/da41b1ba-cb20-478c-890f-359e1da9ab31)  

---

### **7. 3D Customer Segmentation (Age, Income, Spending Score)**
📌 *Observation:*  
- The **yellow and red clusters (high spenders) tend to be younger**, suggesting that youth-oriented marketing strategies may be effective.  

📷 **Screenshot Placeholder:**  
![3D Segmentation](https://github.com/user-attachments/assets/db0a57cc-dae7-4313-9f70-888f01c84d6f)

---

## ✅ **Final Results & Insights**
- **Five customer segments identified**:  
  - **Low-income, low-spenders** – Price-sensitive, require discounts.  
  - **Low-income, high-spenders** – Impulsive buyers, engaged customers.  
  - **High-income, low-spenders** – Untapped potential, need personalized promotions.  
  - **High-income, high-spenders** – Premium buyers, ideal for VIP programs.  
  - **Moderate-income, balanced-spenders** – Frequent shoppers, best for loyalty programs.  

- **Elbow Method confirms that 5 clusters are optimal** for segmentation.  
- **Businesses can use these insights** to tailor marketing strategies and optimize customer experience.  

---

## 🎯 **Future Scope**
- Implement **Hierarchical Clustering** to compare segmentation effectiveness.  
- Integrate **RFM (Recency, Frequency, Monetary) Analysis** for better customer profiling.  
- Develop a **real-time recommendation system** based on customer segments.  

---

## 💡 **How to Use This Repository**
1. Clone this repository:  
   ```sh
   git clone https://github.com/yourusername/CustomerSegmentation-KMeans.git

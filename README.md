🛒 SmartCart Customer Segmentation 

An End-to-End Machine Learning project to segment customers based on their purchasing behavior, age, and tenure using Clustering techniques.

📊 Project Highlights
* **Data Preprocessing:** Handled missing values (Income) using median imputation.
* **Feature Engineering:** Derived `Age` from birth year and `Customer_Tenure` from joining dates.
* **Clustering:** Used Scikit-Learn to group similar customers for targeted marketing.

Bhai, ye raha tumhara perfectly formatted **Professional English README Section**. Isme maine wahi technical terms use kiye hain jo tumhari notebook `smartcart_customers.ipynb` mein hain, jaise **Imputation**, **PCA**, aur **WCSS**.

Ise copy karke apni `README.md` mein paste kar lo:

---

📊 Exploratory Data Analysis & Model Insights

The core findings and model performance of the **SmartCart Segmentation** project are illustrated through the following visualizations:

### 1. Feature Correlation Analysis

A heatmap was generated to identify relationships between different numerical features.

<img width="2344" height="1965" alt="Image" src="https://github.com/user-attachments/assets/08139dda-0adc-404b-9f91-6ee02f44aa75" />

* **Key Insight**: A strong positive correlation was observed between `Income` and `Total_Spending`, serving as a primary driver for customer segmentation.

### 2. Determining Optimal Clusters ($K$)

To ensure model stability, both the **Elbow Method (WCSS)** and **Silhouette Score** were validated.

<img width="1709" height="1237" alt="Image" src="https://github.com/user-attachments/assets/5d8cf32e-8a21-4410-8596-325faf4cb6db" />


* **Key Insight**: Both metrics converge to indicate that **4 Clusters** provide the most distinct and stable segmentation for this dataset.

### 3. 3D Cluster Visualization (PCA)

**Principal Component Analysis (PCA)** was utilized to reduce high-dimensional data into 3D space for intuitive visualization.

<img width="1506" height="1446" alt="Image" src="https://github.com/user-attachments/assets/bf9258ed-e521-46a1-9a52-1938e6a12118" />


* **Key Insight**: The clear spatial separation of data points in 3D space confirms the efficiency of the clustering algorithm.

### 4. Strategic Insight: Income vs. Spending

This visualization is the most crucial for driving business growth and marketing strategy.

* **Key Insight**: Specific segments were identified with high income but low spending—these represent "low-hanging fruit" for personalized promotional offers.

---

<img width="1792" height="1295" alt="Image" src="https://github.com/user-attachments/assets/e0080cbc-793c-4da3-a39b-f885714cb444" />



📁 Repository Structure
* `smartcart_customers.ipynb`: Detailed Step-by-step Analysis and Model Training.
* `smartcart_customers.pkl`: Pre-trained clustering model ready for deployment.
* `requirements.txt`: Python dependencies required to run the project.

🚀 Getting Started
1. Clone the repo:
   ```bash
   git clone https://github.com/rahulshkya/smartcart-clustring.git

2. Install Dependencies:
   ```bash
   pip install -r requirements.txt


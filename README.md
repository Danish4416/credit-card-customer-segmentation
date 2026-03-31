\# Credit Card Customer Segmentation 💳



\## 📌 Problem Statement

A financial company wants to launch a new credit card.  

The goal is to identify the right customer segments to target and recommend appropriate credit limits.



\---



\## 📊 Dataset Used

\- customers.csv → customer demographic details  

\- transactions.csv → customer transaction history  

\- credit\_profiles.csv → credit-related information  

\- avg\_transactions\_after\_campaign.csv → post-campaign behavior  



\---



\## ⚙️ Approach



\### 1. Data Preprocessing

\- Merged datasets using `customer\_id`

\- Handled missing values and outliers



\### 2. Feature Engineering

\- Total spending  

\- Average transaction amount  

\- Transaction frequency  



\### 3. Exploratory Data Analysis (EDA)

\- Spending patterns  

\- Customer comparisons  

\- Data visualizations  



\### 4. Customer Segmentation

\- Applied clustering to group customers  

\- Identified different customer segments  



\---



\## 📈 Key Insights

\- High spenders with strong credit profiles are ideal targets  

\- Moderate users → controlled credit limits  

\- Low activity users → not suitable for high limits  



\---



\## 💡 Business Recommendations

\- Target high-value customers  

\- Assign limits based on behavior  

\- Use segmentation for marketing  



\---



\## 🛠️ Tools \& Technologies

\- Python  

\- Pandas  

\- Matplotlib / Seaborn  

\- Scikit-learn  



\---



\## 🚀 Conclusion

This project helps identify potential customers and supports data-driven credit card decisions.
- Identified 3–4 customer segments
- Recommended target group for credit card launch



\---



\## 📂 Project Structure



Credit\_Card\_Project/

│

├── data/

│   ├── customers.csv

│   ├── transactions.csv

│   ├── credit\_profiles.csv

│   ├── avg\_transactions\_after\_campaign.csv

│

├── credit\_card\_project\_file.ipynb

├── README.md


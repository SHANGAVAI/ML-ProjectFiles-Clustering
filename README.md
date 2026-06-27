# Bank Customer Segmentation using Machine Learning (Clustering) 🏦

## 📌 Project Overview
This project applies unsupervised machine learning techniques to segment bank customers based on their financial profiles and behaviors. By leveraging clustering algorithms, the project transforms raw customer data into distinct, actionable buyer personas, enabling data-driven decision-making for marketing and customer retention strategies.

## 📊 Business Problem
Banks handle vast amounts of customer data but often struggle to deliver personalized financial products. Treating all customers with a one-size-fits-all approach leads to low marketing conversion rates and high customer churn. This project solves that problem by identifying hidden behavioral segments, allowing the bank to target the right customers with the right products (e.g., premium credit cards, investment plans, or basic savings accounts).

## 🛠️ Tech Stack & Tools
- **Language:** Python
- **Environment:** Jupyter Notebook
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-Learn (K-Means Clustering, PCA)

## 🔄 Project Workflow
1. **Data Cleaning:** Handled missing data structures, removed duplicates, and treated outliers to ensure robust model performance.
2. **Exploratory Data Analysis (EDA):** Visualized feature distributions and analyzed correlations between customer income, spending habits, and credit scores.
3. **Feature Engineering & Scaling:** Standardized numerical features using `StandardScaler` to ensure the clustering algorithm gives equal weight to all variables.
4. **Model Building (K-Means):** Utilized the **Elbow Method** and **Silhouette Scores** to determine the optimal number of customer clusters.
5. **Insights Extraction:** Profiled the final clusters to define distinct, actionable business personas.

## 📈 Key Insights & Business Personas
* **The High-Value Investors:** Customers with high income levels but low overall credit spend. This group is an ideal target for premium wealth management and fixed-deposit products.
* **The Active Spenders:** Medium-to-high income individuals with frequent transaction histories and high credit utilization. They should be targeted with cashback rewards and premium credit card upgrades.
* **The Conservative Churn-Risks:** Low-income, low-spending users who interact minimally with the bank. Targeted loyalty programs or lower-fee accounts can improve retention here.
<img width="567" height="448" alt="image" src="https://github.com/user-attachments/assets/0fcc453c-e1f1-4ffc-9713-5321f6afeba6" />
<img width="609" height="432" alt="image" src="https://github.com/user-attachments/assets/17c6c50d-3fe4-40c5-928f-56947d5312f8" />

## 🚀 How to Run the Project
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com
   ```
2. Install the required Python libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   Open the `.ipynb` project file and run all cells sequentially.

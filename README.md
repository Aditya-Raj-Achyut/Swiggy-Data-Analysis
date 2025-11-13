# 🍴 Swiggy Data Analysis

### 📊 Overview  
This project focuses on analyzing Swiggy restaurant data to uncover useful business insights such as:  
- Most popular cuisines  
- Top-rated restaurants  
- City-wise rating trends  
- Cost distribution for two people  

The analysis is done using **Python (Pandas, Matplotlib, and Seaborn)**.

---

### 🧰 Technologies Used  
- **Python 3**  
- **Pandas**  
- **Matplotlib**  
- **Seaborn**  
- **NumPy**  
- **Jupyter / Google Colab**

---

### 📂 Dataset Information  
The dataset contains the following columns:

| Column | Description |
|--------|--------------|
| id | Unique ID of each restaurant |
| name | Restaurant Name |
| city | City where the restaurant operates |
| rating | Average user rating |
| rating_count | Total number of user ratings |
| cost | Average cost for two |
| cuisine | Type of cuisine served |
| lic_no | License number (if available) |
| link | Swiggy link |
| address | Address of the restaurant |
| menu | Menu details |

---

### ⚙️ Steps in the Notebook  
1. **Data Cleaning:**  
   - Removed duplicates and missing values  
   - Converted text columns to numeric where needed  

2. **Exploratory Data Analysis (EDA):**  
   - City-wise average ratings  
   - Cuisine popularity  
   - Rating and cost distributions  
   - Top 10 most-rated restaurants  

3. **Visualizations:**  
   - Bar charts for top cuisines and cities  
   - Histograms for cost and ratings  

---

### 📈 Key Insights  
- 🍕 The most popular cuisines are **North Indian** and **Chinese**  
- 🏙️ The city with the highest average rating is **(your city result)**  
- ⭐ Top restaurants attract a very high number of ratings and good consistency  
- 💰 Average cost for two people is around **₹(your avg cost)**  

## 📊 NYC Taxi Rides – January 2023

### What’s Shown:
- A **scatter plot** visualizing real daily ride counts in NYC during January 2023  
- A **red linear trendline** showing the overall rise/fall in demand over the month

---

### 🛠️ Tools Used:

- **Python** – Core scripting language for data analysis and visualization  
- **Parquet File** – Efficient columnar format used due to the large dataset size (preferred over CSV)  
- **PySpark** – Performed heavy data transformations at scale using distributed processing  
- **Pandas** – Used post-transformation to convert Spark DataFrame into a Pandas DataFrame for easier plotting  
- **NumPy** – Applied to compute and fit a linear regression trendline over date-based ride data  
- **Matplotlib** – Used to plot both scatter data and overlay the trendline visually

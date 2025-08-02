
---

## 🚀 Project Workflow

### 🔹 1. Data Cleaning
- Removed null `CustomerID` and `Description`
- Filtered out returns and invalid `Quantity`/`UnitPrice`
- Created `TotalPrice` column
- Saved clean data to CSV

### 🔹 2. Exploratory Data Analysis (EDA)
- Top products by quantity
- Sales trends over time
- Revenue by country

### 🔹 3. Clustering (RFM + KMeans)
- Created RFM (Recency, Frequency, Monetary) features
- Scaled data and used KMeans to segment customers
- Evaluated with Silhouette Score

### 🔹 4. Power BI Dashboard
- Interactive dashboard with slicers
- Visualized sales trends, customer segmentation, top products/countries
- Added DAX KPIs and AI insights

---

## 📈 Key Insights

- 🇬🇧 United Kingdom is the top customer market
- 🎁 A few products dominate sales volume
- 📆 Holiday months (Nov–Dec) show revenue peaks
- 🧑‍💼 Customer segmentation reveals high-value clusters for targeting

---

## 🧪 How to Run

### 📌 Jupyter Notebook:
```bash
# Install dependencies
pip install pandas matplotlib seaborn scikit-learn

# Open notebook
jupyter notebook notebooks/online_retail_analysis.ipynb
# online-retail-analytics-project

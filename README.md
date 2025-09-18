# 📊 A/B Testing Dashboard — From Data to Decision

## 📝 Project Description
This is my first mini-project in the field of A/B testing using Power BI.  
The goal was to analyze the results of an experiment (Control vs Test) based on an open dataset from Kaggle, calculate key metrics, check statistical significance, and visualize the results in a dashboard.  

📌 Data source: https://www.kaggle.com/datasets/amirmotefaker/ab-testing-dataset?resource=download&select=control_group.csv

---

## 📂 Dataset
The dataset contains results of two groups:
- **Control (A)** — baseline campaign  
- **Test (B)** — experimental campaign  

Each row includes aggregated performance metrics:
- `Impressions` — number of ad impressions  
- `Reach` — unique users reached  
- `Website Clicks` — clicks on the ad  
- `View Content` — content views  
- `Add to Cart` — items added to cart  
- `Purchases` — purchases completed  
- `Spend [USD]` — advertising spend  

---

## 🛠 Workflow
1. **Data Preparation**
   - Loaded Control and Test tables  
   - Combined them into one AB table with a `group` column  

2. **Metric Calculation**
   - Core KPIs: CTR, Conversion Rate (PR(click)), CPC, CPA, CPM  
   - Comparative: Uplift (% and p.p.), Z-score, statistical significance (p<0.05)  

3. **Visualization**
   - KPI cards with key measures  
   - Bar chart comparing Conversion Rate of A vs B  
   - Detailed table with Impressions, Clicks, Purchases, CPA, CPC, CPM, Spend  

---

## 📈 Analysis Results
- **Conversion Rate**:  
  - A = 9.8%  
  - B = 8.6%  

- **Uplift**: –12% (–1.2 p.p.)  

- **Z-score**: –11.84 → statistically significant (p<0.05)  

- **CPA**:  
  - A = $4.53  
  - B = $4.92  

✅ **Conclusion:** Test group B performed worse. The difference is statistically significant.  
**Recommendation** — keep Control A. 

## 🚀 Outcome
This project demonstrates the full analytics cycle:  
**from raw data → to KPIs → to statistical testing → to business decision**.  
It is my first project in A/B testing, and it marks the beginning of a series of portfolio projects in this field. ✨ 

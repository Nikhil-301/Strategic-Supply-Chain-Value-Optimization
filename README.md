# 🚀 Strategic Supply Chain Value Optimization

## Overview

Unlock supply chain excellence using advanced analytics!  
This project leverages powerful data-driven techniques to optimize vendor performance and streamline inventory management. By analyzing historical sales, purchase, and inventory data, we uncover actionable insights for cost reduction, capital liberation, and smarter strategic decisions.

### 🌟 Why This Project?
- **Cut costs & boost profits:** Identify hidden savings and growth opportunities.
- **Visualize performance:** Interactive dashboards & infographics make insights clear and compelling.
- **Drive strategy with data:** Statistically-backed recommendations for vendor management and inventory optimization.

---

## 🔗 Live Demos

Explore interactive tools built from this analysis:

- **[Interactive Dashboard](https://gemini.google.com/share/d3460cbff95e)** – Dynamic visualization of vendor and inventory metrics.
- **[Infographic Summary](https://g.co/gemini/share/0e2f2ea8a624)** – Key findings in an easy-to-digest format.

---

## 🧠 Key Features & Analyses

- **Data Aggregation & Feature Engineering:**  
  Unified diverse datasets (sales, purchases, vendor invoices) into a single `vendor_sales_summary` table using SQL. Engineered critical KPIs: Gross Profit, Profit Margin, Stock Turnover, Sales-to-Purchase Ratio.

- **Exploratory Data Analysis (EDA):**  
  Deep dives: statistical summaries, correlation analyses, and distribution visualizations of core financial metrics.

- **Brand Performance Analysis:**  
  Identified brands with low sales but high profit margins—prime candidates for targeted promotions and pricing tweaks.

- **Top Vendors & Brands:**  
  Ranked and visualized high performers by sales volume, spotlighting major revenue drivers.

- **Vendor Contribution (Pareto Analysis):**  
  Quantified the cumulative impact of top vendors, revealing procurement concentration and dependency.

- **Bulk Purchasing Impact:**  
  Assessed how order size affects unit price, showing up to **72%** cost reduction potential from bulk buying.

- **Inventory Optimization:**  
  Flagged vendors with slow-moving inventory, revealing ~$2.7M in locked-up capital. Proposed strategies for liquidation and improved cash flow.

- **Statistical Hypothesis Testing:**  
  - Calculated 95% Confidence Intervals for profit margins.
  - Ran Two-Sample T-Tests to validate differences between top and low-performing vendors, supporting strategic decision-making.

---

## 💻 Technologies Used

- **Python:**  
  `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy` (ttest_ind, sem, t.ppf)
- **SQL (SQLite):**  
  Data extraction & aggregation
- **Jupyter Notebook:**  
  Interactive analysis & reporting
- **Git/GitHub:**  
  Version control & collaboration
- **HTML/CSS (Tailwind CSS):**  
  Responsive web apps
- **JavaScript (Chart.js):**  
  Dynamic data visualization

---

## 📁 Project Structure

```
.
├── data/
│   └── inventory.db              # SQLite database
├── notebooks/
│   ├── Exploratory Data Analysis.ipynb
│   └── Vendor Performance Analysis.ipynb
├── web_apps/
│   ├── dashboard.html
│   └── infographic.html
├── src/
│   └── ingestion_db.py
├── README.md
└── requirements.txt
```

---

## 🚦 How to Run

**1. Clone the Repository**
```bash
git clone https://github.com/your-username/Strategic-Supply-Chain-Value-Optimization.git
cd Strategic-Supply-Chain-Value-Optimization
```
*(Replace `your-username` and repo name as needed)*

**2. Set Up Python Environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

**3. Install Dependencies**
```bash
pip install -r requirements.txt
```

**4. Database Setup**
Ensure `inventory.db` is in `data/`. If needed, generate it:
```bash
python src/ingestion_db.py
```

**5. Run Jupyter Notebooks**
```bash
jupyter lab
```
Open notebooks in `notebooks/` and explore!

---

## 📊 Results & Insights

- **Bulk Purchasing:** Up to **72%** cost savings identified.
- **Inventory Optimization:** ~$2.7M of capital tied up in slow inventory.
- **Vendor Strategy:** Statistically proven margin differences among vendors drive targeted action.
- **Procurement Dependency:** Over 65% of purchases from top 10 vendors—key risk/opportunity insight.

These findings empower smarter supply chain management, boost profitability, and optimize working capital.

---

## 🚀 Future Enhancements

- Integrate real-time data for live dashboarding.
- Build predictive models for demand forecasting.
- Expand analysis: vendor reliability, lead times, quality metrics.
- Develop richer web apps for business user engagement.

---

## 📬 Contact

**Nikhil Tripathi**  
[tripathinikhil301@gmail.com](mailto:tripathinikhil301@gmail.com)

---

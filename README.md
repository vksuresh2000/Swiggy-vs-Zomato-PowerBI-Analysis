# 🎯 Swiggy vs Zomato: Food-Tech Duopoly Performance Dashboard

An interactive **3-Page Power BI Dashboard** analyzing a structured Kaggle dataset to evaluate India's top two food delivery giants: Swiggy and Zomato.

---

## 🛠️ Tech Stack & Skills Demonstrated
* **Business Intelligence:** Power BI Desktop
* **Data Transformation:** Power Query (ETL, Null handling, Data type corrections)
* **Analytical Modeling:** Advanced DAX Measures (Dynamic aggregations, Profit margin calculations)
* **UI/UX Design:** Integrated Page Navigation & Slicer Reset elements

---

## 📊 Dashboard Architecture

### 🏆 Page 1: Executive Market Outlook (The CEO Lens)
* Aggregated macro KPIs including total platforms transaction volume, revenue distribution, and customer sentiment baseline scores.
* Visualized comparative regional market share splits by city tier using dynamic charts.

### ⚡ Page 2: Operational Efficiency & Fleet Logistics (The Ops Lens)
* Analyzed delivery speed benchmarks side-by-side across various restaurant classifications (`Cloud Kitchen` vs `Casual Dining`).
* Evaluated delivery fee pricing models dynamically scaled against distances from urban city centers.

### 💰 Page 3: Merchant Economics & Profit Optimization (The Business Lens)
* Formulated custom DAX measures to estimate net restaurant payouts after platform commission percentages.
* Evaluated discount frequency distributions against restaurant value tiers to highlight potential pricing traps.

---

## 🚀 Technical Workflow Details

### 1. Data Cleaning (Power Query)
* Eliminating missing records and removing duplicate restaurant listings.
* Formatted categorical descriptions (`restaurant_type`, `price_category`) for clean visuals.

### 2. Business Logic Calculations (DAX)
* Created specialized metrics to split combined metrics back into dedicated platform values.
* Aggregated dynamic multi-city averages without hardcoding values.

---

*Disclaimer: This project is strictly for educational purposes using a simulated dataset from Kaggle and does not reflect official private live operational records of either Swiggy or Zomato.*

# Finance Analytics Dashboard

## 📊 Project Overview
An interactive **Finance Analytics Dashboard in Power BI** designed for a financial organization to monitor transactions, customer behavior, fees, taxes, and performance across segments and regions.  
This project demonstrates **KPI storytelling, demographic insights, and regional analysis** with a robust data model and dynamic interactivity.

---

## 📂 Repository Structure
- `/data` → Raw datasets (`customers.csv`, `finance_transactions.csv`, `Pending_Transaction_Data.csv`)
- `/docs` → Business Requirements document
- `/dashboard` → Dashboard visuals (Finance Analysis, Grid View, Data Model)
- `README.md` → Project overview and documentation

---

## 🚀 Key Features
- **Headline KPIs:**
  - Total Amount: ₹37.32M (↑10.64% YoY)
  - Total Transactions: 3.98K
  - Avg Transaction Value: ₹9.37K
  - Total Fees: ₹56.82K
  - Total Tax: ₹10.25K

- **Visual Insights:**
  - Line chart → Monthly transaction trends
  - Donut chart → Transaction status (Success, Failed, Pending)
  - Bar chart → Customer segment contributions (Retail, Premium, SME, Corporate, Wealth)
  - Map/Bar → State‑wise performance (Maharashtra, Tamil Nadu, Karnataka, etc.)
  - Matrix → Transaction type profitability (Loan EMI, Deposit, Investment, Withdrawal, Refund, etc.)
  - Donut chart → Gender analysis (Male vs Female)

- **Interactivity:**
  - Dynamic filters for Year, Measure, Occupation, Category
  - Drill‑down grid view for transaction‑level records
  - Pending transactions dataset for monitoring unresolved cases

---

## 🗂️ Data Model
- **Calendar Table** → Supports time intelligence (Date, Month, Year)
- **Dynamic Metric Table** → Enables KPI switching
- **Customers Table** → Demographics (Gender, Segment, Occupation, State)
- **Finance Transactions Table** → Transaction details (Type, Status, Amount, Fees, Tax)
- **Pending_Transaction_Data Table** → Isolates pending transactions for risk monitoring

### Relationships
- Calendar ↔ Finance Transactions (Date-based)
- Customers ↔ Finance Transactions (Customer ID)
- Dynamic Metric ↔ KPI visuals (Dynamic measure selection)

---

## 🎯 Business Value
This dashboard enables stakeholders to:
- Monitor KPIs in real time
- Identify high-performing customer segments and states
- Analyze transaction patterns and seasonal trends
- Track operational fees and taxes
- Understand customer demographics
- Detect and monitor pending transactions for operational risk
- Improve financial decision-making and business strategy

---

## 🛠️ Tech Stack
- **Power BI** → Dashboard creation, slicers, drill-downs
- **Excel/CSV** → Data cleaning and preparation
- **GitHub** → Portfolio hosting and documentation

---

## 📖 Usage Guide
1. Clone the repository:
   ```bash
   git clone https://github.com/Karthikeyan00045/Finance-Analytics-Dashboard.git


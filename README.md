# Finance Analytics Dashboard

## 📊 Project Overview
An interactive **Finance Analytics Dashboard in Power BI** designed for a financial organization to monitor transactions, customer behavior, fees, taxes, and performance across segments and regions.

## 📂 Repository Structure
- `/data` → Raw datasets (`customers.csv`, `finance_transactions.csv`)
- `/docs` → Business Requirements document
- `/dashboard` → Dashboard visuals (Finance Analysis, Grid View, Data Model)
- `README.md` → Project overview and documentation

## 🚀 Key Features
- **KPIs:**
  - Total Amount: ₹37.32M (↑10.64% YoY)
  - Total Transactions: 3.98K
  - Avg Transaction Value: ₹9.37K
  - Total Fees: ₹56.82K
  - Total Tax: ₹10.25K

- **Visual Insights:**
  - Monthly transaction trends (Line Chart)
  - Transaction status breakdown (Success, Failed, Pending)
  - Customer segment contribution (Retail, Premium, SME, Corporate, Wealth)
  - State-wise performance (Top regions: Maharashtra, Tamil Nadu, Karnataka)
  - Transaction type profitability (Loan EMI, Deposit, Investment, etc.)
  - Gender-based analysis (Male vs Female)

- **Interactivity:**
  - Dynamic filters for Year, Measure, Occupation, Category
  - Drill-down grid view for transaction-level records

## 🗂️ Data Model
- **Calendar Table** → Time intelligence (Date, Month, Year)
- **Dynamic Metric Table** → Enables KPI switching
- **Customers Table** → Demographics (Gender, Segment, Occupation, State)
- **Finance Transactions Table** → Transaction-level details (Type, Status, Amount, Fees, Tax)

### Relationships
- Calendar ↔ Finance Transactions (Date-based)
- Customers ↔ Finance Transactions (Customer ID)
- Dynamic Metric ↔ KPI visuals (Dynamic measure selection)

## 🎯 Business Value
This dashboard enables stakeholders to:
- Monitor KPIs in real time
- Identify high-performing customer segments and states
- Analyze transaction patterns and seasonal trends
- Track operational fees and taxes
- Understand customer demographics
- Improve financial decision-making and strategy

## 🛠️ Tech Stack
- **Power BI** → Dashboard creation, slicers, drill-downs
- **Excel/CSV** → Data cleaning and preparation
- **GitHub** → Portfolio hosting and documentation

## 📖 Usage Guide
1. Clone the repository:
   ```bash
   git clone https://github.com/Karthikeyan00045/Finance-Analytics-Dashboard.git

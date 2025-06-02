

This project presents a fully interactive, data-driven Power BI dashboard designed to provide actionable insights into customer behavior, loan patterns, deposit trends, and financial risk across various banking segments. By visualizing key metrics and using DAX-driven intelligence, the system helps stakeholders identify risk exposure, customer segments, and strategic opportunities.

---

## 📌 Project Overview

This dashboard enables banking professionals and analysts to:

- Understand customer demographics and financial attributes.
- Track total deposits, loans, and credit card utilization.
- Segment clients by risk weighting, loyalty classification, and income.
- Visualize deposit trends by occupation and account types.
- Monitor loan-to-deposit ratios to minimize financial risk.

---

## 🎯 Objectives

- To create a professional BI dashboard for banking analytics using Power BI.
- To identify high-risk, low-income clusters using scatter plots.
- To build DAX measures for KPI monitoring (credit utilization, deposits, etc.).
- To segment customers by loyalty, risk, and occupation.
- To offer executive-level summaries for business decision-making.

---

## 🗂️ Repository Structure
📁 Banking-Intelligence-Dashboard/
├── 📊 PowerBI_Dashboard.pbix
├── 📄 Banking_Report.docx
├── 📈 Screenshots/
│ ├── Home_Page.png
│ ├── Loan_Credit_Analysis.png
│ ├── Deposit_Analysis.png
│ ├── Customer_Profile.png
│ └── Summary_Dashboard.png
├── 📁 Data/
│ ├── banking_dataset.csv
│ ├── correlation_matrix.csv
├── 📑 README.md
└── 📜 License


---

## 📊 Dashboard Pages

| Page No. | Title                     | Key Insights & Visuals                          |
|----------|---------------------------|--------------------------------------------------|
| 1        | **Home Page**             | KPIs, Deposits, Loans, Correlation, Slicers     |
| 2        | **Loan & Credit Analysis**| Credit card balance, business lending, DAX cards|
| 3        | **Deposit Analysis**      | Deposits by account type, income vs deposits    |
| 4        | **Customer Profiling**    | Age bands, loyalty segments, risk scatter plot  |
| 5        | **Summary Dashboard**     | Executive overview, gauge charts, Top 5 insights|

---

## 🧠 Technologies Used

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **CSV Dataset (Pre-cleaned)**
- **Python / Excel (for correlation pre-processing)**

---

## 📈 Key Metrics (DAX)

- `TotalClients = DISTINCTCOUNT('Banking'[Client ID])`
- `TotalDeposits = SUM('Banking'[Bank Deposits])`
- `AvgCardUtilization = DIVIDE(SUM(Credit Card Balance), SUM(Credit Cards))`
- `LoanToDepositRatio = DIVIDE(SUM(Loans), SUM(Deposits)) * 100`

---

## 📝 How to Use

1. Download or clone this repository.
2. Open `PowerBI_Dashboard.pbix` using **Power BI Desktop**.
3. Replace `banking_dataset.csv` in the data source path if needed.
4. Explore pages using slicers, filters, and visuals.
5. Export PDF reports or share dashboard via Power BI Service.

---

## 🔐 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙋 Author & Acknowledgements

**Author:** Ananya Goswami 
Certified Data Analyst

---

## 📞 Contact

For queries, contributions, or suggestions:  
📧 goswamiananya009@gmail.com  
🔗 LinkedIn / GitHub: https://www.linkedin.com/in/ananyagoswami7/ / https://github.com/Ananyagoswami009



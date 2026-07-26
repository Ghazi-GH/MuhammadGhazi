# Corporate Commercial Sales Performance & Workforce Productivity Dashboard

## 🎯 The Problem
Commercial operations and enterprise sales leadership often lack real-time clarity into how individual sales reps and management tiers contribute to top-line growth. Without a centralized business intelligence interface linking macro revenue trends ($96.62M total revenue, 1.12M units sold) to sales team hierarchies, product portfolios, and granular transactional logs, executives struggle to identify top-performing sales managers, isolate underperforming products, and audit high-value deals.

## 🛠️ The Technical Action
I built a dual-view **Enterprise Commercial Sales Dashboard** in Power BI to monitor sales volume, product performance, and workforce productivity:

### 1. High-Level Executive Dashboard (Page 1)
* **Core KPI Metrics:** Configured high-level metrics displaying overall enterprise health ($96.62M Revenue, 1.12M Units Sold).
* **Supervisory Hierarchy Analysis:** Formulated a proportional doughnut breakdown isolating market share by team leads (e.g., Supervisor-1 commanding 31.08% / $30M, Supervisor-4 at 24.22% / $23M).
* **Product Catalog Revenue Diagnostics:** Structured a dynamic bar chart ranking top-revenue product SKUs (highlighting Product-7 at $5.9M, Product-27 at $5.5M, and Product-15 at $5.2M).
* **Temporal Trend Mapping:** Tracked month-over-month revenue velocity from Jan 2019 through Apr 2019 to evaluate seasonal momentum.
* **Employee Revenue Contribution:** Built a comparative visual mapping individual sales rep contributions across the organization (EMP-1 to EMP-20).

### 2. Granular Transaction Audit Table (Page 2)
* Designed a transactional audit view detailing individual line items by `Date`, `EMP ID`, `EMP Name`, `Supervisor`, `Product ID`, `Unit Sold`, and total `Revenue`.
* Implemented multi-parameter dynamic slicers (`Date`, `Product ID`, `Product Name`, `EMP Name`, `Supervisor`) allowing executive auditors to cross-filter specific sales reps or high-ticket orders instantly.

---

## 🚀 Key Operational Insights
* **Supervisor Allocation Balance:** Identified that sales volume is heavily weighted toward Supervisor-1 (31.08%), revealing opportunities to rebalance client accounts across other supervisory teams to optimize deal throughput.
* **Product Revenue Concentration:** Isolated core revenue drivers (Product-7, Product-27, and Product-15 account for a significant share of total revenue), enabling targeted inventory management and targeted sales campaigns.
* **Audit Transparency:** Provides sales directors with immediate line-item traceability from high-level $45,000 single-order transactions down to individual rep performance.

---

### 📸 Dashboard Interface Snapshots
#### Page 1: Executive Sales & Workforce Performance Overview
[Commercial Sales Executive Overview](sales_executive_overview.png)

#### Page 2: Transactional Sales Audit & Line-Item Explorer
[Commercial Sales Transaction Audit](sales_transaction_audit.png)

---
### 🔗 Live Interactive Link
* 🌐 **[Launch Interactive Commercial Sales Analytics Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMzM5OWFlODktZmM3My00ZGMwLWFlZWItMzRjMmQ0NDlkMjdiIiwidCI6ImY4ZTJkM2E5LWM1YmQtNGY0Zi04MTdjLWQ4NzEzMDY2ZjFjZiJ9)**

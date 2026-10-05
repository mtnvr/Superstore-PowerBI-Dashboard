# 🛒 Superstore Sales Dashboard — Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0D9488?style=for-the-badge&logo=microsoft&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-14B8A6?style=for-the-badge)

---

## 📌 Project Overview

An interactive **Power BI Dashboard** built on the classic Superstore dataset, analyzing sales performance across products, regions, customers, and time periods. Designed with a professional **dark navy theme** and 25 custom DAX measures.

---

## 📊 Dashboard Pages

| Page | Description |
|---|---|
| 🏠 **Executive Summary** | Top-level KPIs, sales trends, region & segment breakdown |
| 📦 **Sales & Product Analysis** | Category, sub-category, top 10 products, scatter analysis |
| 🗺️ **Geographic & Shipping** | Filled map by state, delivery days, top 10 cities |
| 📈 **YoY Growth & Trends** | Year-over-year comparison, YTD metrics, trend table |
| 💬 **Tooltip - Detail** | Custom hover tooltip showing KPIs + category breakdown |

---

## 🧮 DAX Measures (25 Total)

### 📂 KPIs
| Measure | Description |
|---|---|
| Total Sales | Sum of all sales |
| Total Profit | Sum of all profit |
| Profit Margin % | Profit ÷ Sales |
| Order Count | Distinct order count |
| Avg Delivery Days | Average shipping time |
| Total Customers | Distinct customer count |
| Avg Order Value | Sales ÷ Orders |
| Total Quantity | Total units sold |
| Loss Orders | Orders where Profit < 0 |

### 📂 KPIs \ Sales vs Target
| Measure | Description |
|---|---|
| Sales Target | 110% of Total Sales (target baseline) |
| Sales vs Target | Variance: Actual vs Target |
| Target Achievement % | Sales ÷ Target |
| Target Status | ✅ On Target / ⚠️ Near / 🔴 Below |

### 📂 KPIs \ Retention
| Measure | Description |
|---|---|
| Customer Retention Rate | Current vs Prior Year customers |
| Revenue per Customer | Sales ÷ Total Customers |

### 📂 Time Intelligence
| Measure | Description |
|---|---|
| Prior Year Sales | SAMEPERIODLASTYEAR Sales |
| Prior Year Profit | SAMEPERIODLASTYEAR Profit |
| YoY Sales Growth | % change vs prior year |
| Sales MoM Growth % | Month-over-month growth |
| Sales YTD | Year-to-date Sales |
| Profit YTD | Year-to-date Profit |

### 📂 Rankings
| Measure | Description |
|---|---|
| Product Sales Rank | RANKX by product |
| Top 10 Products Sales | Returns BLANK for rank > 10 |
| City Sales Rank | RANKX by city |
| Top 10 Cities Sales | Returns BLANK for rank > 10 |

---

## 📈 Key Insights

| Metric | Value |
|---|---|
| 💰 Total Sales | $2,296,919 |
| 📈 Total Profit | $286,409 |
| 📊 Profit Margin | 12.47% |
| 🛒 Total Orders | 5,009 |
| 👥 Total Customers | 793 |
| 📦 Avg Delivery Days | 3.96 days |
| 📅 YoY Sales Growth | 46.89% |
| 🎯 Target Achievement | 90.9% |

### ⚠️ Notable Findings
- **Furniture** category has only **2.5% margin** vs 17% for Technology
- **Central region** has the lowest margin at **7.9%**
- **1,870 (37%)** of all orders are loss-making
- **West region** leads with $725K in sales and 14.9% margin

---

## 🎨 Theme & Design

| Element | Value |
|---|---|
| Background | `#0F1F38` Deep Navy |
| Card Background | `#162843` Navy Mid |
| Primary Accent | `#14B8A6` Teal |
| Secondary | `#F59E0B` Amber |
| Alert / Negative | `#F43F5E` Rose |
| Font | Segoe UI |

---

## 🗂️ Repository Structure

```
Superstore-PowerBI-Dashboard/
│
├── 📊 Superstore_Project.pbix     ← Main Power BI file
├── 📄 README.md                   ← This file
├── 📁 screenshots/
│   ├── page1_executive.png
│   ├── page2_products.png
│   ├── page3_geographic.png
│   └── page4_trends.png
└── 📁 data/
    └── superstore_data.csv        ← Source dataset (optional)
```

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **DAX** (Data Analysis Expressions)
- **Superstore Dataset**
- **Power Query (M)**

---

## 🚀 How to Use

1. Download **Superstore_Project.pbix**
2. Open with **Power BI Desktop** (free download from Microsoft)
3. Navigate pages using the **bottom page tabs**
4. Use **slicers** to filter by Year, Category, Region, Segment
5. **Hover** over any visual to see the custom tooltip
6. **Ctrl+Click** navigation buttons to move between pages

---

## 👤 Author

**Tanveer**
- Power BI Developer & Data Analyst
- Specializing in DAX, Financial Dashboards & Data Profiling

---

## 📃 License

This project is open source and available under the [MIT License](LICENSE).

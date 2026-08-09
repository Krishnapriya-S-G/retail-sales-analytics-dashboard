\# 📊 Retail Sales \& Customer Analytics Dashboard



An end-to-end data analytics project analyzing 1M+ UK retail transactions using Python, SQL, and Power BI. Built a 3-page interactive dashboard covering executive KPIs, product/sales performance, and customer behavior analytics.



\## 🎯 Project Overview



This project demonstrates a complete data analytics workflow:

\- \*\*Data Cleaning\*\*: Handled missing values, duplicates, and invalid entries using Python (Pandas)

\- \*\*Data Analysis\*\*: Explored trends and patterns using SQL

\- \*\*Data Visualization\*\*: Built an interactive, multi-page Power BI dashboard with cross-page filtering



\## 📁 Dataset



\*\*Source\*\*: \[UCI Online Retail II Dataset (Kaggle)](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci)



Raw and cleaned data files are not included in this repository due to size limits. To reproduce this analysis, download the dataset from the link above and run `analysis.ipynb`.



\## 🧹 Data Cleaning Summary



Starting from 1,067,371 raw transactions, the following cleaning steps were applied:



| Step | Rows Removed | Reason |

|------|--------------|--------|

| Cancelled orders | 19,494 | Invoice starting with 'C' |

| Missing descriptions | 4,382 | Incomplete product info |

| Duplicate records | 34,335 | Exact duplicate rows |

| Negative quantity/price | Removed | Data entry errors |

| Non-product entries | Removed | Postage, adjustments, etc. |



\*\*Final dataset\*\*: 1,003,520 clean transaction records



\## 📈 Dashboard Pages



\### Page 1: Executive Dashboard

\- Key metrics: Total Orders, Revenue, Customers

\- Monthly revenue trend (2009–2011)

\- Top 10 products and countries by revenue



\### Page 2: Product \& Sales Analytics

\- Total quantity sold, average order value, unique products

\- Monthly quantity trend

\- Top products by quantity sold

\- Revenue by day of week



\### Page 3: Customer Analytics

\- Total customers, repeat customers, average revenue per customer

\- Monthly active customers trend

\- New vs. returning customer split

\- Top 10 customers by revenue



All pages include synchronized \*\*Year\*\* and \*\*Country\*\* slicers for interactive filtering.



\## 🔑 Key Insights



\- Identified a strong seasonal revenue spike in November (both 2010 and 2011), suggesting holiday-driven demand

\- United Kingdom accounts for 90%+ of total revenue; EIRE and Netherlands are the next largest markets

\- Top customer generated £580K+ across 145 orders; one customer generated £168K in just 2 orders (bulk buyer pattern)

\- 72% of customers are returning customers, indicating strong customer retention



\## 🛠️ Tools Used



\- \*\*Python\*\* (Pandas) — data cleaning and transformation

\- \*\*SQL\*\* (SQLite) — data analysis and querying

\- \*\*Power BI\*\* — interactive dashboard design and visualization



\## 📸 Dashboard Screenshots



\### Executive Dashboard

!\[Executive Dashboard](screenshots/Page1\_Executive\_Dashboard.png)



\### Product \& Sales Analytics

!\[Product \& Sales Analytics](screenshots/Page2\_Product\_Sales\_Analytics.png)



\### Customer Analytics

!\[Customer Analytics](screenshots/Page3\_Customer\_Analytics.png)



\## 📂 Repository Structure

retail-sales-analytics-dashboard/

├── analysis.ipynb                  # Python data cleaning \& SQL analysis

├── retail\_sales\_dashboard.pbix     # Power BI dashboard file

├── Screenshots/                    # Dashboard page screenshots

└── README.md



👤 Author



Krishnapriya S G — Aspiring Data Analyst



Data Source: UCI Online Retail II Dataset | Built with Python, SQL \& Power BI


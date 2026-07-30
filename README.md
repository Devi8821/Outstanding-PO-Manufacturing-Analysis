# 📊 Outstanding Purchase Order Analysis Dashboard

> **Power BI Portfolio Project | Manufacturing Industry (Rattan Factory - Mojokerto)**

Transforming a raw Purchase Order report into an interactive dashboard that helps stakeholders monitor outstanding orders, identify urgent Purchase Orders, and support operational decision-making.

---

## 📌 Project Overview

This project was developed based on a real business request from a manufacturing company.

The stakeholder wanted to answer two simple but important questions:

> **1. Which Purchase Orders are truly urgent?**  
> **2. How can we identify overdue supplier deliveries?**

Instead of building a dashboard immediately, I started by understanding the business problem, cleaning the data, validating business assumptions, and transforming the dataset into an analysis-ready database before performing the analysis.

---

# 📈 Executive Summary

| KPI | Result |
|------|--------|
| Active Purchase Orders | **31 PO** |
| Outstanding Quantity | **85,994 Units** |
| Completion Rate* | **5.1%** |
| Analysis Period | **2025 – 2026** |
| Dashboard Pages | **Executive Overview & Open PO Monitoring** |

> *Completion Rate is calculated based on the available Outstanding VDL dataset.

---

# 🚩 Business Problem

Before analysis, several data challenges were identified.

- Raw Excel report contained **merged cells**
- Missing values required cleaning
- Shipment Week contained text values such as **ASAP** and **WEEK XX**
- Shipment Due Date did not exist
- Supplier information was unavailable

After discussing with the stakeholder, an important business rule was established:

> **ASAP = Maximum delivery lead time of 60 days (2 months).**

This assumption became the foundation for creating **Shipment Due Date**, which was later used to identify overdue Purchase Orders.

---

# 🔄 Analytics Process

```text
Business Understanding
        │
        ▼
Data Cleaning & Transformation
        │
        ▼
Business Rules Definition
        │
        ▼
DAX Development
        │
        ▼
Dashboard Development
        │
        ▼
Business Insights & Recommendations
```

### Activities

- ✅ Built an analysis-ready database
- ✅ Cleaned and transformed raw data
- ✅ Handled missing values
- ✅ Created Shipment Due Date
- ✅ Developed business logic using DAX
- ✅ Built an interactive Power BI dashboard
- ✅ Generated business insights and recommendations

---

# 📊 Key Insights

| Finding | Detail |
|----------|--------|
| 📦 Outstanding Orders | Approximately **86K units** remain outstanding and require operational monitoring. |
| 🚚 Shipment Monitoring | Shipment Due Date enables the business to identify overdue Purchase Orders more effectively. |
| ⚠️ Priority Identification | Priority Levels help distinguish urgent Purchase Orders from those that can still be monitored. |
| 👥 Customer Impact | Dashboard highlights customers affected by outstanding orders for better prioritization. |
| 📉 Data Limitation | Supplier performance could not be evaluated because supplier information was unavailable. |

---

# 💡 Business Recommendations

- Prioritize Purchase Orders classified as **Overdue** or **Critical**.
- Review shipment schedules regularly to reduce overdue orders.
- Include **Supplier ID** in future reports to enable supplier performance analysis.
- Standardize operational reports to eliminate merged cells and improve reporting quality.
- Use the dashboard as a routine operational monitoring tool for faster decision-making.

---

# 🛠 Tools & Skills Demonstrated

### Tools

- Microsoft Excel
- Power Query
- Power BI
- DAX

### Skills

- Data Cleaning
- Data Transformation
- Data Modeling
- Business Understanding
- DAX Development
- Dashboard Design
- KPI Development
- Data Storytelling
- Business Insight
- Business Recommendation

---

# 📂 Repository Structure

```text
📁 data
 ├── Outstanding VDL (Raw Data).xlsx
 └── Outstanding VDL (Clean Data).xlsx

📁 dashboard
 └── Outstanding VDL Dashboard.pbix

📁 images
 ├── Executive Overview.png
 ├── Open PO Monitoring.png
 └── Dashboard Preview.png

README.md
```

---

# 📚 Key Learning

This project strengthened my understanding that:

- Data analysis starts with understanding the business problem—not building dashboards.
- Data quality directly impacts the reliability of insights.
- Business assumptions should always be validated with stakeholders.
- Data limitations must be documented to avoid misleading conclusions.
- A good dashboard should support decision-making, not just display data.

---

# 🚀 Business Value

This dashboard helps stakeholders:

- Monitor Outstanding Purchase Orders in one place.
- Identify urgent and overdue Purchase Orders.
- Prioritize operational follow-ups.
- Improve shipment monitoring.
- Support faster, data-driven business decisions.

---

# 📁 Files

| File | Description |
|------|-------------|
| 📊 Power BI Dashboard (.pbix) | Interactive dashboard for Executive Overview & Open PO Monitoring |
| 📄 Dataset (.xlsx) | Raw and cleaned Purchase Order data |
| 🖼 Dashboard Preview | Dashboard screenshots |
| 📘 README.md | Project documentation |

---

# 📫 Questions or Feedback?

I'd be happy to connect and discuss Data Analytics, Business Analytics, Power BI, or dashboard development.

📧 **Email**  
deviau.ok01@gmail.com

💼 **LinkedIn**  
https://www.linkedin.com/in/dauliaoktaviona

💻 **GitHub**  
https://github.com/Devi8821

---

⭐ **If you found this project helpful, feel free to give this repository a star or connect with me on LinkedIn. Feedback and discussions are always welcome!**

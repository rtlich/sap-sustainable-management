# SAP-Sustainable-Management
Project for the ERP &amp; BI course at Esprit School of Engineering. It optimizes resource and operations management in an agri-food company using SAP MM &amp; PM, focusing on sustainability, CO₂ reduction, and predictive maintenance.

     # 🛠️ SAP Data Integration with Talend

![Talend](https://img.shields.io/badge/Talend-FF6D70.svg?style=for-the-badge&logo=talend&logoColor=white)
![SAP](https://img.shields.io/badge/SAP-0FAAFF.svg?style=for-the-badge&logo=SAP&logoColor=white)
![Sustainability](https://img.shields.io/badge/SDG-2030-2ea44f?style=for-the-badge)

## 🌟 Project Overview
**Optimizing agri-food operations** through SAP MM/PM integration with environmental KPIs:

- 📦 **Inventory Optimization** (Stock levels, demand forecasting)
- ⚙️ **Predictive Maintenance** (Equipment monitoring)
- 🌱 **CO₂ Tracking** (Emissions analysis, carbon storage)

[📊 View Full HTML Version](README.html) | [🚀 Quick Start](#-quick-start)

---

## 📊 Key Performance Indicators

| KPI | Formula | Threshold |
|-----|---------|-----------|
| 🧮 **Inventory Optimization Index** |  DIVIDE(SUM('Fact_Ressource'[Current_Stock]), SUM('Fact_Ressource'[Stock_Initial])) * 100 | ≥80% = Optimal |
| 🌿 **Supplier Sustainability** | `Renewable Energy % + Certifications` | ≥70 = Excellent |
| ⚡ **Revenue_contibution** | `divide(sum(Fact_Ressource[Expected_revenue]),52300000)`  |
| 🚀**Total_products_sold** |sum(Fact_Ressource[Stock_Initial])-sum(Fact_Ressource[Current_Stock])

 

---

## 🛠️ Tech Stack

### 🔌 Core Integration
<p>
  <img src="https://img.icons8.com/color/48/talend.png" alt="Talend" width="40"/>
  <img src="https://img.icons8.com/color/48/sap.png" alt="SAP" width="40"/>
  <img src="https://img.icons8.com/color/48/mysql.png" alt="MySQL" width="40"/>
</p>

### 📂 Data Sources
```plaintext
├── SAP Tables (MARD, QMEL)
├── Equipment.xlsx
├── Climate_Environmental_Data.json
└── Suppliers.csv

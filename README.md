# :octocat:Dashboard👇
![Screenshot 2023-07-28 152259](https://github.com/yashdoshi12/Sales_report_using_PowerBi/assets/39629707/23e117f3-fd1d-4c0b-a0a7-391795d3ca79)

<hr />
<br />

# 📊 Amazon Sales Dashboard – Power BI Analytics
### 🚀 Interactive Business Insights | Automated KPI Tracking | Data-Driven Decision Making

![Dashboard Preview](images/dashboard-preview.png)

---

## ⭐ Overview
The **Amazon Sales Dashboard** is an interactive Power BI solution designed to help businesses monitor, analyze, and optimize sales performance. It provides real-time insights into **Revenue**, **Profit**, **Orders**, **Regional Performance**, and **Product Category Trends**.

Built with **Power BI, Excel & Power Query**, this solution automates data transformation and reporting—reducing manual work by **40%**.

---

## 🧠 Key Features
- 📈 Sales Performance KPIs  
- 🌍 Regional Insights  
- 🏷 Category Analysis  
- 🔢 Advanced DAX Measures  
- ⚡ Automated ETL using Power Query  
- 🔄 Clean & Refreshable Data Model  

---

## 🛠 Technologies Used
- Power BI  
- Excel  
- Power Query  
- DAX  
- Python (optional ETL)

---

## 📁 Project Structure
```
Amazon-Sales-Dashboard/
│── data/
│── dax/
│── scripts/
│── images/
│── powerquery/
│── report_layout/
│── theme/
│── README.md
```

---

## 🔢 DAX Measures (KPIs)
### Total Sales
```DAX
Total Sales = SUM(SalesFact[Sales])
```

### Profit Margin %
```DAX
Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)
```

### Sales YoY Growth
```DAX
Sales YoY Growth =
VAR CY = CALCULATE([Total Sales], YEAR(Calendar[Date]) = YEAR(TODAY()))
VAR LY = CALCULATE([Total Sales], YEAR(Calendar[Date]) = YEAR(TODAY()) - 1)
RETURN DIVIDE(CY - LY, LY)
```

---

## 💡 Insights & Outcomes
✔ Identified best-selling categories  
✔ Found high-performing regions  
✔ Reduced reporting time by **40%**  
✔ Enabled data-driven decision-making  

---

## 🎯 Future Enhancements
- ML-based forecasting  
- Integration with Amazon API  
- RFM customer segmentation  

---

## 📬 Contact
**Author:** Sri Harsha Vardhan Chadaram  
📧 Email: sriharshavardhanchadaram@gmail.com  
🔗 GitHub: https://github.com/sriharshavardhan  
🔗 LinkedIn: https://linkedin.com/in/sriharsha

# <div align="center">Don't forget to leave a star ⭐️</div>
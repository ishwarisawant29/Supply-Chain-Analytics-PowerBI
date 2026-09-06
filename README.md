# 📊 Supply Chain and Logistics Analytics

## 📌 Project Overview

**Supply Chain and Logistics Analytics** is a Power BI project developed to analyze supply chain performance and convert raw transaction data into meaningful business insights.

The project uses the **SupplyChain360 Integrated Supply Chain Analytics Dataset** containing **15,000 supply chain transaction records**. Microsoft Power BI is used for data transformation, data modelling, DAX calculations, KPIs, interactive filters, and data visualization.

The dashboard provides insights into revenue, profit, orders, product sales, inventory availability, supply chain costs, defect rate, supplier lead time, and location performance.

---

## 🎯 Objectives

* Analyze supply chain performance using Power BI.
* Organize data into a structured multi-table model.
* Create relationships between fact and dimension tables.
* Develop KPIs using DAX.
* Analyze revenue, profit, orders, costs, and inventory.
* Identify product and location performance.
* Analyze defect rate and supplier lead time.
* Create an interactive dashboard for data-driven decision-making.

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* **CSV**
* **Data Modelling**
* **Star Schema**
* **Data Visualization**
* **Business Intelligence**

---

## 📂 Project Files

```text
Supply-Chain-Analytics-PowerBI/
│
├── Report.pbix
├── SupplyChain.csv
├── Product.csv
├── Location.csv
├── Date.csv
├── Supply-Chain-Analytics-Documentation.pdf
└── README.md
```

---

## 🗃️ Dataset

The project contains **15,000 supply chain transaction records**.

### Fact Table

**SupplyChain**

Contains transaction-level information such as:

* Transaction ID
* Date ID
* Product ID
* Location ID
* Products Sold
* Revenue Generated
* Stock Levels
* Order Quantity
* Shipping Time
* Shipping Cost
* Manufacturing Cost
* Manufacturing Lead Time
* Defect Rate
* Transportation Cost
* Availability
* Supplier Lead Time

### Dimension Tables

**Product**

* Product information
* Product type

**Location**

* Location and regional information

**Date**

* Date and time-related information

---

## 🔗 Data Model

The project follows a **Star Schema** consisting of one central fact table and three dimension tables.

```text
                 Product
                    │
                    │
Location ───── SupplyChain ───── Date
```

Relationships:

```text
Product  → SupplyChain
Location → SupplyChain
Date     → SupplyChain
```

All relationships use **one-to-many (1:*) cardinality** with filtering from the dimension tables toward the fact table.

---

## 📈 Key Performance Indicators

| KPI                        |  Value |
| -------------------------- | -----: |
| Total Revenue              |  ₹341M |
| Total Profit               |  ₹127M |
| Total Transactions         |    15K |
| Profit Margin              | 37.38% |
| Inventory Availability     | 92.41% |
| Average Defect Rate        |  9.98% |
| Average Supplier Lead Time |  17.45 |

---

## 📊 Dashboard Analysis

The Power BI dashboard provides analysis of:

* Revenue trends over time
* Revenue by location
* Product sales by product type
* Supply chain cost breakdown
* Inventory availability
* Defect rate
* Supplier lead time
* Manufacturing cost
* Shipping cost
* Transportation cost

### Interactive Filters

The dashboard includes slicers for:

* Product Type
* Location
* Date

---

## 🔍 Key Insights

* Total revenue is approximately **₹341 million**.
* Calculated profit is approximately **₹127 million**.
* Profit margin is approximately **37.38%**.
* Manufacturing contributes approximately **84.72%** of total recorded supply chain costs.
* Inventory availability is approximately **92.41%**.
* Average defect rate is approximately **9.98%**.
* Cosmetics has the highest product sales at approximately **2.38 million units**.
* Average supplier lead time is approximately **17.45 time units**.

---

## 💡 Recommendations

* Reduce manufacturing costs to improve overall profitability.
* Improve quality control to reduce the defect rate.
* Monitor supplier lead time to minimize delays.
* Maintain optimal inventory availability.
* Focus inventory planning on high-demand products.
* Monitor location-wise revenue performance.

---

## 🚀 How to Use

1. Download or clone this repository.
2. Open **`Report.pbix`** using Microsoft Power BI Desktop.
3. Keep the CSV files in the same folder.
4. Refresh the data if required.
5. Explore the dashboard using the available filters and visualizations.

---

## ⚠️ Limitations

* The dataset contains 15,000 transaction records and is designed for analytical purposes.
* Calculated profit is a **profit proxy** based on the costs available in the dataset.
* Salaries, taxes, marketing, and administrative expenses are not included.
* The dashboard provides high-level supply chain analysis.
* Results depend on the accuracy and structure of the available dataset.

---

## 📌 Conclusion

This project demonstrates the practical use of **Power BI, Power Query, DAX, data modelling, KPIs, and interactive visualization** for supply chain and logistics analytics.

The dashboard converts raw supply chain data into meaningful insights that can support **data-driven decision-making and supply chain performance analysis**.

---

## 👩‍💻 Project

**Supply Chain and Logistics Analytics**

**Developed using Microsoft Power BI**

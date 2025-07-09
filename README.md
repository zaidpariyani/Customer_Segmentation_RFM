# Customer Segmentation Using RFM Analysis

This project focuses on identifying and grouping customers based on their purchasing behavior using the RFM (Recency, Frequency, Monetary) model. The goal is to support better marketing decisions, improve customer retention, and boost business profitability by understanding who the key customer segments are.

---

## 🧠 Project Objective

To perform RFM segmentation on customer transaction data and create a Power BI dashboard that highlights key customer groups like Loyal Customers, Big Spenders, New Customers, and At-Risk Customers. This enables data-driven decisions for personalized targeting and strategy planning.

---

## 📁 Dataset Description

The dataset contains historical transaction data for an online retailer, sourced from Kaggle.  
It includes the following columns:

- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

After cleaning and transformation, a `TotalRevenue` column was created by multiplying `Quantity × UnitPrice`.

---

## 🛠️ Tools Used

- **Excel**: Initial cleaning and formatting
- **Python (Google Colab)**: RFM score calculation and customer segmentation
- **Power BI**: Visualization and dashboard creation

---

## 🔢 RFM Metrics Used

- **Recency**: Days since last purchase  
- **Frequency**: Number of transactions  
- **Monetary**: Total amount spent by the customer  

Each metric was scored from 1 to 5. Based on these, customers were grouped into segments.

---

## 🧩 Customer Segments Created

| Segment       | Description                              |
|---------------|------------------------------------------|
| Loyal         | Frequent and recent buyers               |
| Big Spender   | High spenders with average recency       |
| At Risk       | Previously active, now inactive          |
| New           | Recent buyers with limited transactions  |
| Others        | General group that doesn’t fit above     |

---

## 📊 Dashboard Visuals in Power BI

- 💡 **KPI Cards**  
  - Total Revenue  
  - Average Recency  
  - Total Customers  

- 📊 **Bar Chart** – Customers by Segment  
- 📈 **Pie Chart** – Revenue Contribution by Segment  
- 🧮 **Matrix Table** – Average Recency, Frequency, and Monetary by Segment  
- 🎛️ **Segment Slicer** – Filter dashboard by segment type

> All visuals are fully interactive using slicers.

---

## 📸 Screenshots

Inside the `screenshots/` folder:
- `dashboard_overview.png`
- `bar_segment_count.png`
- `matrix_segment.png`
- `slicer_demo.png`
- `kpi_cards.png`

---

## 📁 Folder Structure

Customer_Segmentation_RFM/
├── OnlineRetailRFM_Clean.xlsx
├── rfm_output.xlsx
├── Customer_Segmentation_RFM.pbix
├── README.md
└── screenshots/


---

## 🔍 Key Insights

- Loyal and Big Spender customers drive the majority of revenue.
- At Risk customers had high value in the past but show declining engagement.
- New customers present an opportunity for retention campaigns.

---

## 👨‍💻 About Me

I'm Mohammed Zaid Pariyani, currently pursuing Final Year of Master of IT with a focus on Business Analytics.  
This project helped me apply core analytics skills including data preparation, RFM modeling, and dashboard creation. I’m passionate about using data to solve real-world business problems and create value through insights.

---

## 🔗 License

This project is open-source and intended for educational and portfolio purposes.

# Supply Chain Delay Analysis

## The Business Question

A supply chain can generate strong sales and profit while still facing delivery problems. This project focused on understanding **where delivery delays occur and what patterns exist across regions, markets, shipping modes, categories, products, and time**.

Using the DataCo Supply Chain dataset, I analyzed approximately **181K orders from 2015–2018** and built an interactive Power BI dashboard to identify areas where delivery performance could be improved.

---

## Starting With the Bigger Picture

The dataset contained **181K orders**, generating **$36.78M in sales** and **$3.97M in profit**. The overall **delay rate was 19.9%**, with an average shipping time of **3.50 days**.

The overall KPI provided the starting point, but I needed to break the data down to understand where delays were concentrated.

---

## Looking at Delivery Performance

The delivery-status analysis showed that **57.29% of orders were classified as late deliveries**, while **24.07% were advance shipments** and **18.64% were shipped on time**.

This made delivery reliability the main focus of the analysis.

---

## Where Were Delays Happening?

Regional analysis showed clear differences in delay rates:

| Order Region   |    Delay % |
| -------------- | ---------: |
| Southeast Asia | **25.38%** |
| Eastern Asia   | **24.90%** |
| South Asia     | **24.12%** |
| Oceania        | **23.47%** |
| Western Europe | **20.60%** |

**Southeast Asia recorded the highest delay rate at 25.38%**, while Western Europe recorded 20.60%.

Market-level analysis also showed variation, with **Pacific Asia recording the highest delay rate among the markets displayed**.

---

## How Did Delays Change Over Time?

The monthly trend showed relatively stable delay rates from **February to September**, followed by a noticeable increase from **October through December**.

This suggests that seasonal factors such as **higher demand, inventory pressure, carrier capacity, or fulfillment workload** could be investigated further.

---

## Comparing Shipping Modes

Shipping mode showed a significant difference in delivery performance:

| Shipping Mode  |    Delay % |
| -------------- | ---------: |
| First Class    | **36.22%** |
| Second Class   | **29.00%** |
| Same Day       | **17.73%** |
| Standard Class | **14.54%** |

**First Class had the highest delay rate at 36.22%, while Standard Class had the lowest at 14.54%.**

This difference makes carrier performance, routes, and promised delivery times important areas for further investigation.

---

## Looking at Categories and Products

The category analysis showed higher delay percentages for categories including **Golf Bags & Carts, Lacrosse, Pet Supplies, Cameras, and Strength Training**.

At the product level, several products had substantially higher delay rates than the overall 19.9%:

| Product                             | Orders | Delayed |    Delay % |
| ----------------------------------- | -----: | ------: | ---------: |
| SOLE E25 Elliptical                 |     10 |       7 | **70.00%** |
| Ogio Rage Golf Shoes                |     61 |      42 | **68.85%** |
| GoPro HERO3+ Black Edition Camera   |     32 |      21 | **65.63%** |
| Titleist Small Wheeled Travel Cover |     54 |      34 | **62.96%** |

The **SOLE E25 Elliptical had the highest delay rate at 70%**, showing how specific products can perform very differently from the overall supply chain.

---

## Key Insights

The analysis revealed that delivery delays were **not evenly distributed**.

Regional rates ranged from **20.60% to 25.38%** among the highlighted regions, while shipping-mode rates ranged from **14.54% to 36.22%**. Delays also increased toward the end of the year, and some individual products recorded delay rates above **60%**.

This shows that the **19.9% overall delay rate alone does not tell the full story**. Breaking the data down by region, market, time, shipping mode, category, and product reveals specific areas that require attention.

---

## How Could Delivery Performance Be Improved?

The dashboard identifies where delays occur, but not their exact causes. The next step would be to investigate high-delay segments using **carrier, warehouse, inventory, supplier, and route-level data**.

High-delay regions and markets could be reviewed for logistics performance, while shipping modes with higher delay rates could be evaluated for carrier and route efficiency. Products with consistently high delays could be investigated for **inventory availability, supplier lead times, and fulfillment locations**.

The increase in delays from **October to December** also suggests the need for stronger **peak-season inventory and logistics planning**.

---

## Conclusion

The analysis found an overall **19.9% delay rate**, but delivery performance varied significantly across different parts of the supply chain.

The key takeaway is that **delays should not be addressed using a single overall KPI**. Identifying high-delay regions, shipping modes, time periods, categories, and products provides a more targeted approach to improving delivery performance.

Connecting these findings with operational data would help the business move from identifying **where delays happen** to understanding **why they happen** and taking targeted action to improve on-time delivery.

---

## Dashboard

I built the analysis as a **two-page interactive Power BI dashboard**.

### Page 1 — Supply Chain Performance Overview

KPIs for **Total Orders, Sales, Profit, Delayed Orders, Delay %, and Average Shipping Days**, along with sales trends, delivery status, sales by market, sales by country, and shipping-mode analysis.

### Page 2 — Delivery Delay Analysis

**Delay % by shipping mode, market, order region, category, and month**, along with product-level delay analysis, average/max delay days, and on-time orders.

Interactive filters allow analysis by **Year, Market, and Shipping Mode**.

---

## Tools & Skills

**Power BI | DAX | Power Query | Data Modeling | Data Cleaning | KPI Development | Time-Series Analysis | Geographic Analysis | Interactive Dashboard Development**

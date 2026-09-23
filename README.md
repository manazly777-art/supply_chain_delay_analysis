# Supply Chain Delay Analysis

## The Business Question

A supply chain can generate strong sales and profit while still facing delivery problems. This project focused on understanding **where delivery delays occur and what patterns can be found across regions, markets, shipping modes, categories, products, and time**.

Using the DataCo Supply Chain dataset, I analyzed approximately **181K orders from 2015–2018** and built an interactive Power BI dashboard to explore delivery performance.

---

## Starting With the Bigger Picture

The dataset contained **181K orders**, generating **$36.78M in sales** and **$3.97M in profit**. The overall **delay rate was 19.9%**, with an average shipping time of **3.50 days**.

These numbers provided an overall view of the business, but I wanted to understand **where the delays were happening**.

---

## Looking at Delivery Performance

The delivery-status analysis showed that **57.29% of orders were classified as late deliveries**, while **24.07% were advance shipments** and **18.64% were shipped on time**.

This showed that delivery performance was an important area to explore further.

---

## Where Were Delays Happening?

Regional analysis showed differences in delay rates:

| Order Region   |    Delay % |
| -------------- | ---------: |
| Southeast Asia | **25.38%** |
| Eastern Asia   | **24.90%** |
| South Asia     | **24.12%** |
| Oceania        | **23.47%** |
| Western Europe | **20.60%** |

**Southeast Asia had the highest delay rate at 25.38%**, while Western Europe recorded 20.60%.

The market analysis also showed differences between markets, with **Pacific Asia having the highest delay rate among the markets displayed**.

---

## How Did Delays Change Over Time?

The monthly trend showed that delay rates stayed fairly stable from **February to September**, before increasing from **October through December**.

This could be related to factors such as **higher order volumes, increased demand, or more pressure on delivery services during the later months of the year**.

---

## Comparing Shipping Modes

There were noticeable differences in delay rates between shipping modes:

| Shipping Mode  |    Delay % |
| -------------- | ---------: |
| First Class    | **36.22%** |
| Second Class   | **29.00%** |
| Same Day       | **17.73%** |
| Standard Class | **14.54%** |

**First Class had the highest delay rate at 36.22%, while Standard Class had the lowest at 14.54%.**

This shows that delivery performance varied depending on the shipping method and would be worth investigating further.

---

## Looking at Categories and Products

The category analysis showed higher delay percentages for categories including **Golf Bags & Carts, Lacrosse, Pet Supplies, Cameras, and Strength Training**.

At the product level, some products had much higher delay rates than the overall 19.9%:

| Product                             | Orders | Delayed |    Delay % |
| ----------------------------------- | -----: | ------: | ---------: |
| SOLE E25 Elliptical                 |     10 |       7 | **70.00%** |
| Ogio Rage Golf Shoes                |     61 |      42 | **68.85%** |
| GoPro HERO3+ Black Edition Camera   |     32 |      21 | **65.63%** |
| Titleist Small Wheeled Travel Cover |     54 |      34 | **62.96%** |

The **SOLE E25 Elliptical had the highest delay rate at 70%**, showing that some individual products had much higher delay rates than the overall supply chain.

---

## Key Insights

The analysis showed that delivery delays were **not the same across all parts of the business**.

Regional delay rates ranged from **20.60% to 25.38%** among the highlighted regions, while shipping-mode delay rates ranged from **14.54% to 36.22%**. Delays also increased toward the end of the year, and some individual products had delay rates above **60%**.

This shows why looking only at the overall **19.9% delay rate** is not enough. Breaking the data down by region, market, month, shipping mode, category, and product gives a clearer picture of where delays are more common.

---

## How Could Delivery Performance Be Improved?

Based on these findings, a few areas could be looked at more closely.

**Regions with higher delay rates** could be checked to understand whether the issue is related to the delivery service, location, or shipping method.

**Shipping modes with higher delay rates**, especially First Class at **36.22%**, could be compared with the other shipping options to understand why their performance is different.

**Products with very high delay rates** could be checked to see whether there are problems with product availability, stock levels, or where the products are being shipped from.

Since delays also increased between **October and December**, the business could prepare better for this period by making sure enough stock and delivery capacity are available.

These are areas for further investigation rather than confirmed causes, since the current dataset does not contain enough information to identify the exact reason for each delay.

---

## Conclusion

The analysis found an overall **19.9% delay rate**, but delivery performance varied across regions, markets, months, shipping modes, categories, and products.

The key takeaway is that **one overall delay percentage does not tell the complete story**. Looking at the data from different angles helped identify the areas where delays were more common.

Further analysis using information such as **delivery companies, stock levels, warehouses, and shipping routes** could help understand the reasons behind these delays and find ways to improve on-time delivery.

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

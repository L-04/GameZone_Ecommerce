<div align="center">

# **E-commerce Performance Report**

</div>

<div align="center">
  
## Client Background

</div>


**GameZone** is an emerging e-commerce retailer established in 2019, specialising in high-performance gaming hardware, peripherals, and digital accessories. Launching just before the global shift in digital entertainment consumption, GameZone experienced a massive surge in demand as the "home gaming" market exploded.

Today, **GameZone** manages a global supply chain, serving a customer base of approximately **20,000** users and with total historical revenue exceeding **$6 million**. The Ecommerce data available spans dimensions and metrics such as sales, product, sales by region, and refunds by product.

Reporting to the Head of Operations, an in-depth analysis was conducted to evaluate **GameZone's** performance over the past several years (2019–2021). This comprehensive review provides valuable insights that internal cross-functional teams will utilise to streamline processes and enhance **GameZone's** commercial performance. The key insights and recommendations focus on the following areas:


### Northstar Metrics

- **Sales trends - Focusing on key metrics of sales revenue, number of orders placed, and average order value (AOV) across the 2019-2021 period.**
- **Product performance - Analyzing different product lines, market impact, and refund rates to inform strategic product decisions.**
- **Channel effectiveness - Assessing different marketing channels to inform decisions in future marketing campaigns.**
- **Regional dynamics - Evaluating regional demand and product performance within regions to identify areas for improvement.**

<br>




<div align="center">
  
# **Executive Summary**

</div>

<br>
<br>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://res.cloudinary.com/dsz6plni9/image/upload/v1772034391/Sales_Revenue_Light_xgmrqg.png">
    <source media="(prefers-color-scheme: dark)" srcset="https://res.cloudinary.com/dsz6plni9/image/upload/v1772034669/Sheet_18_2_1_csrv4e.png">
    <img width="1000" alt="Monthly sales bar chart showing peaks and dips from 2019-2022" src="https://res.cloudinary.com/your-account/image/upload/v1234567890/light-chart.png">
  </picture>
</div>

<table>
  <tr>
    <td width="50%" valign="top">

### 1. Revenue Growth and Peak Performance
- **2020 was the strongest year**, with sales consistently growing each quarter as a result of the COVID-19 pandemic.
- **Q4 2020 saw the highest revenue** ($550k in December 2020), making it the best-performing period.
- **January & February 2021 ($540k)** also maintained strong sales, though a we see a sharp downward trend start.

### 2. Declining Trend in 2021
- A sales anomaly and significant decline occurred at the start of 2021 with **January ($289K), February ($248K)** which whilst stronger than previous Q1's to date, is still a sharp downturn from previous months.
- The Q1 revenue decline suggests a major downturn, likely caused by external market conditions, reduced consumer demand, or internal operational shifts.

    </td>
    <td width="50%" valign="top">

### 3. Quarterly Insights & Seasonal Trends
- **Q3 and Q4 of each year** typically show strong performance, likely due to seasonal shopping trends and marketing efforts.
- **September & October** typically follow the same pattern of a quick jump in sales in September, followed by a sharp fall in October which suggests a macro economic trend or seasonal 'lull' in the lead up to black friday sales.

### 4. Key Takeaways & Recommendations
- **Investigate the causes** of the 2021 decline (e.g., market changes, competition, internal factors).
- **Leverage high-performing periods** (e.g., Q3 and Q4 of strong years) to refine marketing and sales strategies.
- **Reassess business strategy for the remaining of 2021 and 2022**, focusing on pricing, promotions, and customer engagement to regain momentum especially for historically weaker months.

    </td>
  </tr>
</table>



<div align="center">
  
## **Dataset Structure and ERD (Entity Relationship Diagram)**

</div>

The database structure as seen below consists of four tables: **Orders**, **Customers**, **Geography**, and **Order_Status**, with a total row count of 22,865 records.

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://res.cloudinary.com/dsz6plni9/image/upload/v1772040463/Screenshot_2026-02-21_at_16.02.32_dodnrl.png">
    <source media="(prefers-color-scheme: light)" srcset="https://res.cloudinary.com/dsz6plni9/image/upload/v1772040704/Screenshot_2026-02-25_at_17.33.01_txdoko.png">
    <img width="680" alt="Entity Relationship Diagram showing tables: orders, customers, geo_lookup, and order_status" src="https://res.cloudinary.com/dsz6plni9/image/upload/v1772040704/Screenshot_2026-02-25_at_17.33.01_txdoko.png">
  </picture>
</div>




  <h1 align="center">Insights Deep-Dive</h1>

<h2 align="center">Sales Trend</h2>

#### Total Sales Revenue
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://res.cloudinary.com/dsz6plni9/image/upload/v1772470518/Total_Sales_Dark_Line_izkqhp.png">
    <source media="(prefers-color-scheme: light)" srcset="https://res.cloudinary.com/dsz6plni9/image/upload/v1772470526/Total_Sales_Light_Line_imym6o.png">
    <img width="600" alt="Total sales revenue line graph over time" src="https://res.cloudinary.com/dsz6plni9/image/upload/v1772470526/Total_Sales_Light_Line_imym6o.png">
  </picture>
</div>

**1. The Peak Performance Period**
- Historically, **Q4 (Oct-Dec) has been the strongest quarter** likely due to holiday shopping (Black Friday, Cyber Monday, Christmas sales).
- **December 2020 recorded the highest revenue at $550k**. This represents a **~200% increase from the month** in previous years, likely caused by the pandemic as well as expert timing from the marketing teams.
- A puzzling September–October pattern: sales rise in September (2019: +24%, 2020: +15%), only to fall in October (2019: -22%, 2020: -25%) - making **October Q4's weakest month every year**

**2. Sharp Decline in Q1 2021 - A Major Anomaly**
- Historically sales tend to dip during post-holiday seasons. However, sales experienced a dramatic collapse from December 2020 to January 2021,**almost returning to early pandemic levels within a single month**
- Typically, we see revenue has normalised by February/March. **Unusually, February 2021 saw further decline** rather than recovery, suggesting deeper structural issues beyond typical seasonality
- Historically, **we have seen sales increase ~70% from January to February** as post-holiday spending rebounds. In 2021, we saw a **~15% decrease instead** - a complete reversal of the expected trend. Combined with the **~50% collapse from December to January**, this marks some of the **lowest revenue seen since the start of COVID**

---

#### Average Order Value (AOV)
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://res.cloudinary.com/dsz6plni9/image/upload/v1772471770/AOV_Dark_uv4sbd.png">
    <source media="(prefers-color-scheme: light)" srcset="https://res.cloudinary.com/dsz6plni9/image/upload/v1772471766/AOV_Light_r417lu.png">
    <img width="600" alt="Average order value line graph over time" src="https://res.cloudinary.com/dsz6plni9/image/upload/v1772471766/AOV_Light_r417lu.png">
  </picture>
</div>

**1. A sharp surge, followed by a sudden decline**
- **AOV spiked sharply in 2020, peaking at $329 in December 2020** compared to 2019's peak of $253 in November - a 30% increase that aligns with the pandemic-driven e-commerce boom
- **Early 2021 saw AOV fall to $290**, a 10% decline that warrants marketing team attention - while seasonal dips are expected, the magnitude suggests potential factors like shifting product mix or promotional strategy changes. This suggests increased price sensitivity as economic uncertainty grew or as lower-priced alternatives entered the mix

**2. The September-October Pattern**
- Despite sales consistently falling from September to October, **AOV moves in the opposite direction**, suggesting a shift toward premium purchasing
- **AOV increases from $305 in September 2020 to $327 in October 2020 (8% rise)**, even as sales drops 25%. We see the same in 2019 as **AOV increases from $237 to $242 even as sales drop 24%**
- **This points to a segment of loyal, less price-sensitive buyers** who continue purchasing regardless of seasonal dips - likely early adopters, brand enthusiasts, or customers with higher disposable income



---

#### Order Volume
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://res.cloudinary.com/dsz6plni9/image/upload/v1772471792/OrderCount_Dark_keudsj.png">
    <source media="(prefers-color-scheme: light)" srcset="https://res.cloudinary.com/dsz6plni9/image/upload/v1772471788/OrderCount_Light_npvbzu.png">
    <img width="600" alt="Number of orders line graph over time" src="https://res.cloudinary.com/dsz6plni9/image/upload/v1772471788/OrderCount_Light_npvbzu.png">
  </picture>
</div>

**1. Channel Performance**
- Direct channel dominates all others by a significant margin
- Email was the only channel showing growth in 2021 while others plummeted

**2. Regional Patterns**
- Complete sales dip across all products in North America
- PS5 in APAC and Lenovo in EMEA showed growth in early 2021 despite global decline
- Nintendo Switch experienced a nearly 20% refund rate in early 2021

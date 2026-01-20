# 🛒 Superstore Sales Intelligence & Forecasting — Tableau Analytics Project 📈

This project delivers an end-to-end analytical exploration of a retail superstore’s sales performance using Tableau. It combines historical performance analysis, geographic and segment insights, category-level growth patterns, and forward-looking sales forecasting to support strategic decision-making.

The dashboards are designed with **executive storytelling**, **clean visual hierarchy**, and **actionable business insights**, making them suitable for stakeholders across operations, sales, and strategy teams.

---

## 📊 Live Tableau Dashboards

1️⃣ **Superstore Sales Overview — Performance & Distribution**  
[https://public.tableau.com/shared/HQJSK4NKK?:display_count=n&:origin=viz_share_link]

2️⃣ **Sales Forecast — Actuals vs. Projections**  
[https://public.tableau.com/shared/PGZQG36RZ?:display_count=n&:origin=viz_share_link]

3️⃣ **Category & Sub-Category YoY Growth Analysis**  
[https://public.tableau.com/shared/J8TKKYM5X?:display_count=n&:origin=viz_share_link]

---

## 📁 Dataset Source

**Kaggle Dataset: https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting**  
The dataset represents a fictional retail superstore and includes:
* **Order-Level Transactions:** Sales, order dates, ship dates, quantities.
* **Customer Attributes:** Segment, region, state.
* **Product Hierarchy:** Category and sub-category.
* **Geographic Dimensions:** State-level sales distribution.

---

## 🎯 Project Objectives

* Provide a **holistic executive overview** of sales, customers, orders, and logistics.
* Analyze **temporal trends** across years, quarters, and months.
* Identify **geographic sales concentration** and regional contribution.
* Understand **customer segment behavior** and regional demand patterns.
* Evaluate **category and sub-category YoY growth dynamics**.
* Develop a **forward-looking sales forecast** to support capacity and revenue planning.
* Translate analytics into **clear business takeaways** and strategic recommendations.

---

## 🔑 Key Features & Insights

## Dashboard 1️⃣: Superstore Sales Overview
<img width="1365" height="804" alt="Superstore Overview Dashboard" src="https://github.com/user-attachments/assets/overview-placeholder" />

A high-level executive snapshot of retail performance.
* 💰 **Strong Revenue Base:** Total sales of **$2.3M** supported by **4,922 orders** and **793 customers**.
* 🗺️ **Geographic Concentration:** Sales are heavily concentrated in high-performing states, with clear regional dominance patterns.
* 👥 **Customer Segmentation:**  
  * **Consumer (50.76%)** drives the majority of revenue  
  * **Corporate (30.44%)** provides stable secondary demand  
  * **Home Office (18.79%)** remains a smaller but consistent segment
* 📦 **Operational Context:** Shipment lead time metrics highlight logistics scale and fulfillment complexity.
* 📈 **Quarterly Growth:** Clear YoY expansion with accelerating quarterly sales contributions toward later years.

---

## Dashboard 2️⃣: Sales Forecast — Actuals vs. Estimated Projections
<img width="1360" height="762" alt="Superstore Forecast Dashboard" src="https://github.com/user-attachments/assets/forecast-placeholder" />

A time-series analysis comparing historical actuals against projected future sales.
* 📉 **Short-Term Volatility, Long-Term Growth:** Actual sales fluctuate week-to-week but follow a strong upward trend.
* 🌦️ **Seasonality Effects:** Repeating spikes and dips indicate cyclical demand patterns.
* 🚀 **Growth Acceleration:** Forecast projects a sharp upward trajectory beyond recent actuals.
* 🔮 **Forecast Band Insight:** Widening confidence intervals reflect increasing uncertainty typical of high-growth phases.
* 🧠 **Strategic Signal:** Recent actuals closely track forecast estimates, increasing confidence in projections.

**Business Takeaway:**  
The organization is entering a **high-growth phase**, requiring proactive planning in inventory, staffing, and revenue strategy to capture upside while managing volatility.

---

## Dashboard 3️⃣: YoY Sales Growth by Category & Sub-Category
<<div class='tableauPlaceholder' id='viz1768928847866' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;23&#47;23B5P7S4N&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;23B5P7S4N' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;23&#47;23B5P7S4N&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1768928847866');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1500px';vizElement.style.height='850px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1500px';vizElement.style.height='850px';} else { vizElement.style.width='100%';vizElement.style.height='2750px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>>

A deep dive into category-level and sub-category-level performance from 2015–2018.
### 🪑 Furniture
* **Chairs** consistently lead as the top-performing sub-category.
* Growth is **stable and volume-driven**, making Furniture a dependable revenue base.

### 🗂️ Office Supplies
* Exhibits the **highest volatility** across years.
* Strong rebounds in **Binders, Storage, and Appliances** after early dips.
* Presents optimization opportunities through **inventory control and demand forecasting**.

### 💻 Technology
* **Phones and Copiers** act as primary growth engines.
* Delivers **high-impact revenue growth** but with higher variability.
* Indicates dependence on larger or enterprise-style deals.

**Strategic Takeaways:**
* Double down on **Technology**, especially Phones and Copiers.
* Stabilize **Office Supplies** by addressing high-variance sub-categories.
* Leverage **Furniture** as a predictable foundation for long-term planning.

---

## 🛠️ Tech Stack

* **Tableau Public** — Data modeling, calculated fields, forecasting, and visual analytics.
* **Excel / CSV** — Source data format.
* **Mapbox / OpenStreetMap** — Geographic visualization.

---

## 🚀 Future Enhancements

* Add **profitability and margin analysis** by category and region.
* Introduce **discount sensitivity** and promotion impact analysis.
* Expand forecasting with **scenario-based projections**.
* Build a **KPI-driven executive summary dashboard**.
* Integrate supply-chain metrics such as fulfillment delays and return rates.

---

## 👤 Author

**Sai Mohit Gadam**  
📍 Vancouver, BC  
📧 [mohitgadam10@gmail.com](mailto:mohitgadam10@gmail.com)  
🔗 [Tableau Public Profile](https://public.tableau.com/app/profile/sai.mohit.gadam4520)

---

⭐ If you found this project insightful, feel free to star the repository or connect with me on Tableau Public.

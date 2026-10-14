# 🛒 E-Commerce Advanced Data & Statistical Analytics

An end-to-end, enterprise-level data analytics project focusing on e-commerce transactions, sales dynamics, conversion funnels, and statistical hypothesis testing. The project integrates BigQuery SQL, Python, and Tableau to extract business-critical insights and offer strategic recommendations.

---

## 📌 Project Overview & Objectives
The primary objective of this project was to analyze large-scale e-commerce transactional data to identify key revenue drivers, optimize marketing/traffic channels, evaluate user behavior across tech stacks, and validate business hypotheses using statistical testing methods.

---

## 🛠️ Tech Stack & Skills
* **SQL & Cloud Querying:** Google BigQuery (relational querying, chained `LEFT JOIN`, aggregation, filtering)
* **Python Analytics Stack:** Pandas, NumPy, SciPy (Statistical Tests)
* **Data Visualization:** Matplotlib, Seaborn, Tableau
* **Business Intelligence:** Interactive Dashboard in Tableau
* **Statistical Methods:** ANOVA Testing, Correlation Analysis, Hypothesis Testing (t-tests/group comparisons)

---

## 📊 End-to-End Analytical Pipeline

1. **BigQuery Data Retrieval & Pipeline Setup:**
   * Established a connection with Google BigQuery to retrieve relational e-commerce tables (`sessions`, `orders`, `products`, `accounts`).
   * Maintained session population integrity via structured relational joins.

2. **Data Cleaning & Quality Assurance:**
   * Managed date/time conversions, boolean parsing, string normalization, and missing value treatment.

3. **Exploratory Data Analysis (EDA):**
   * **Geographic & Category Insights:** Revenue distribution per continent/country and breakdown of top-selling products (e.g., *Sofas & Armchairs*, *Chairs*, *Beds*).
   * **Device & Tech Stack Breakdown:** Performance analysis across OS/browsers using **RPS (Revenue Per Session)**.
   * **User Behavior:** Email verification rates, newsletter subscription impacts on total revenue.

4. **Sales Dynamics & Seasonality:**
   * Analyzed weekly sales trends identifying peak pre-holiday performance (mid-December >$3.5M/week) and post-holiday slowdowns.

5. **Pivot Table & Multi-Dimensional Segmentation:**
   * Session distribution across traffic channels (Organic, Paid, Direct) segmented by device types.

6. **Statistical Analysis & Hypothesis Testing:**
   * **Correlation Analysis:** Evaluating relationships between sessions, traffic channels, and overall revenue.
   * **ANOVA Testing:** Testing daily sales differences across top geographic continents.
   * **Group Comparisons:** Statistical hypothesis testing comparing behavior between registered vs. guest users.

---

## 💡 Key Findings & Strategic Business Recommendations

* 💰 **Total Performance:** Generated **$31.97M+ in total revenue** across **349,545 orders**.
* 🖥️ **Primary Sales Driver:** **Desktop Chrome** users generate the highest order volume (204.4k orders), outperforming Mobile (137.2k orders).
* 🔎 **Traffic Channels:** **Organic Search** is the most effective acquisition source (124.4k orders / 72.6k Desktop sessions), followed closely by **Paid Search** (94.3k orders).
* 🌍 **Core Markets:** **Americas** (led by the US) dominates global volume (peaking at $6.85M in Dec). Category demand remains uniform across top markets (*Sofas*, *Chairs*, *Beds*).
* 📊 **RPS Highlights:** Identified high-value tech stack outliers (e.g., Macintosh/Edge users yielding higher RPS on lower sample sizes) while maintaining stable baseline RPS ($91–$95) on mainstream Chrome/Safari setups.
* 🚀 **Recommendation:** Optimize the **Mobile Sales Funnel** to bridge the revenue gap with Desktop, and focus marketing/inventory planning on top-performing core furniture categories.

---

## 🔗 Interactive Dashboard
* 📊 **Tableau Dashboard:** https://public.tableau.com/app/profile/bartosz.cho.odzi.ski/viz/Portfolioproject1_17868868340750/Dashboard1

---

## 👤 Author
**Bartosz Chołodziński**
* 💼 LinkedIn: https://www.linkedin.com/in/bartosz-cholodzinski
* 📧 Email: bartosz.cholodzinski@gmail.com

# retail-store-sales-performance-powerbi
Interactive 5-page Power BI dashboard with a Star Schema (7 tables), YoY% analysis via Calculation Groups, and actionable business insights on margins, discounts, and shipping logic.
#  Retail Stores Performance & Sales Matrix (Power BI)

##  Project Overview & Business Context
This project focuses on building a production-ready, multi-page Power BI dashboard to monitor a global retail store network. The goal was to transform raw sales logs into strategic insights, analyze year-over-year (YoY) growth, evaluate profit margins, and identify critical operational bottlenecks across product categories and logistics.

---

##  Data Architecture & Engineering
* **Data Modeling:** Developed an optimized **Star Schema** consisting of 1 Fact table and 6 Dimension tables (7 tables total) in Power BI Desktop to establish clear filter contexts and high performance.
* **Advanced DAX & Calculation Groups:** Engineered reusable business metrics using complex DAX (including `CALCULATE` and `TOTALYTD`). Implemented **Calculation Groups** to dynamically compute Year-over-Year (YoY%) changes across multiple metrics simultaneously.
* **Advanced UX/UI Features:** Developed 5 interactive report pages embedded with **Drill-through** and **Drill-up** actions, enabling users to seamlessly navigate from high-level country summaries down to specific store metrics.

---

##  Executive Insights & Key Findings
1. **The Growth Paradox:** Annual revenue scales effectively, exhibiting a strong **26% to 32% YoY growth rate**; however, the overall **Profit Margin stagnates at 12%**.
2. **Aggressive Discounting Risk:** Marketing discounts exceeding 40% eliminate profitability. The *Tables* category, with an average discount of 29%, is the only product vector operating in the negative, resulting in a **-$64K net loss**.
3. **Logistics Bottleneck:** The *First Class* shipping method suffers from a **75% delay rate**, proving to be the most expensive yet least reliable delivery tier.
4. **Return Rate Leakage:** Product returns account for 4% of total sales, draining **$526K in revenue annually**.

##  Strategic Conclusion
While the business successfully expands its revenue footprint, top-line sales growth will fail to convert into bottom-line net profit without a systematic optimization of the discounting policy and immediate correction of logistical inefficiencies.

---
## 📢 Business Presentation
I have prepared a strategic analytical presentation based on this Power BI report, highlighting the core business insights, identified leaks, and data-driven recommendations for stakeholders.

👉 **[View the Executive Presentation (PDF)](./Retail_Store_Analysis_Presentation.pdf)**

---
## 📂 Repository Contents
* `Retail_Store_Performance_Suite.pbix` — Full Power BI Desktop application file (including Data Model, Power Query M steps, and layouts).
* `Retail_Store_Analysis_Presentation.pdf` — PDF version of the business presentation.
* `README.md` — Strategic business brief.

*For a comprehensive view of my analytics workflow, interactive live reports, and complete case studies, visit my **[Notion Portfolio](ВСТАВТЕ_СЮДИ_ПОСИЛАННЯ_НА_ВАШ_NOTION)**.*



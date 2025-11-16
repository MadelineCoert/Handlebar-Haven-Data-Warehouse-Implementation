# Handlebar Haven Data Warehousing Project
---

## Final Report  
**[🔗 View the full PDF report here](Handlebar_Haven_Data_Warehousing_Implementation.pdf)**  
*A complete breakdown of the dimensional model, ETL workflows, business insights and strategic recommendations.*

This project implements an end-to-end data warehouse for Handlebar Haven, a global bicycle manufacturer and retailer. It includes dimensional modelling, ETL development using SSIS, SQL-based data integration and analytical reporting of key performance drivers across customers, products, territories and time periods.

The goal was to design and deliver a scalable analytics environment capable of supporting evidence-based decision-making and enabling strategic insights on profitability, product performance and regional growth opportunities.

---

## Project Overview

- **Client:** Handlebar Haven  
- **Role:** Data Engineer / Analyst  
- **Tools Used:** SSIS, SQL Server, MySQL, Visual Studio  
- **Dataset:** Operational sales, product, customer, supplier and territory tables  
- **Deliverables:** Dimensional model, ETL pipeline, warehouse schema, insights report

---

## Key Insights

- **High-value customers are concentrated in the U.S.:** San Francisco and the broader West Coast generate the strongest customer profitability.
- **Top-margin products outperform top-selling ones:** The Classic Vest (Medium) and Bike Wash Dissolver deliver the highest profit despite moderate sales volume.
- **Northwest U.S. is the leading territory:** Profit in this region is nearly double that of the Southwest.
- **Profit peaks in March and Q1:** May has the highest sales volume, but March produces superior margins. Sundays are the most profitable day of the week.
- **Underperforming product lines identified:** Scooter racks, caps, forks, derailleurs and headsets consistently return low profit and present opportunities for rationalisation.

---

## Recommendations

- **Expand in top-performing U.S. regions:** Increase stock availability, targeted marketing and retailer engagement in the Northwest and key U.S. states.
- **Promote high-margin products:** Prioritise the Classic Vest (M) and Bike Wash Dissolver in inventory planning and promotional campaigns.
- **Replicate Northwest operational strengths elsewhere:** Analyse contributing factors such as product mix and fulfilment efficiency, then scale best practices to other regions.
- **Rationalise low-value categories:** Remove persistent underperformers to reduce overhead and reallocate resources.
- **Optimise seasonal timing:** Leverage March and Q1 high-margin periods for targeted campaigns while using May’s higher sales volume for broader promotions.

---

## Techniques Applied

- Development of a **Kimball-style star schema** aligned with business processes  
- **ETL design** with SSIS: extraction, cleansing, transformation and loading  
- Creation of **conformed dimensions** (Product, Time, Territory) for consistent reporting  
- Derivation of key profitability metrics for analytical queries  
- SQL-driven analysis to uncover customer, product and territory performance trends  
- Data interpretation to produce strategic insights and recommendations

---

## Repository Structure
HandlebarHaven-DataWarehouse/
├── README.md # Project overview
├── Handlebar_Haven_Data_Warehousing_Implementation.pdf # Final full report
├── etl/ # SSIS package files and transformation logic

---

## Reflections

This project strengthened my skills in dimensional modelling, ETL development and analytical SQL. I gained practical experience in building scalable data warehouse architecture, managing complex transformations and translating warehouse outputs into strategic business recommendations. Future extensions could include predictive forecasting, automated reporting pipelines and inventory optimisation models.

---

## Author

**Madeline Coert**  
Graduate Certificate in Business Analytics – University of Queensland  

📍 Brisbane, Australia  
📧 madelinecoert@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/madeline-coert-546667309)


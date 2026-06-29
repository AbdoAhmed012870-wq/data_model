# data_model

## Project Overview
An enterprise-grade Power BI solution designed to analyze sales performance, track financial targets, and optimize regional revenue distribution using an optimized Star Schema data model.

## Technical Skills Demonstrated
* **Advanced Data Modeling (Star Schema):** Designed efficient relational models utilizing standard industry practices to separate core business transactions (`Fact Tables`) from descriptive lookup tables (`Dimension Tables`).
* **Granularity & Relationship Management:** Established reliable `1-to-many` relationships across multiple business dimensions, implementing optimized cross-filter directions to enhance DAX efficiency and prevent ambiguity.
* **Data Cleansing & Transformation (ETL):** Organized clean surrogate keys (e.g., `Customer Key`, `Employee Key`, `City Key`) to map business operations accurately across diverse data streams.

## Data Model Architecture
Below are the semantic database schemas built and optimized for the analytics workflows in this project:

### 1. Revenue & Target Management Model
![Revenue Model](sales_data_model.png)

### 2. Customer & Operations Analytics Model
![Customer Model](sales_profit_data_model.png)

---
*Note: You can download the `.pbix` file above to inspect the relationship cardinalities, cross-filter directions, and the full semantic model.*

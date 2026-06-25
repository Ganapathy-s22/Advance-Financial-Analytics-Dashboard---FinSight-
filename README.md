# FinSight - Advanced Financial Analytics Dashboard

This project is an end-to-end Data Analytics solution designed to provide real-time insights into financial transactions, customer behavior, and operational risks across multiple regions and business segments.

## 📊 Project Overview & Business Story
A financial organization needed a centralized analytical solution to monitor transaction performance, track operational fees/taxes, and identify high-performing customer segments. 

Instead of working with a simple flat file, I took on a professional enterprise-level data scale containing **50,000+ transaction records** and **5,000 unique customer profiles** to transform raw logs into actionable business intelligence.

## ⚙️ The Data Pipeline & Technical Architecture
To handle this data scale effectively, I designed a production-grade data pipeline:

1. **Data Wrangling & Preprocessing (Python / Pandas):** 
   - Handled large-scale messy data fields, resolved formatting inconsistencies, and aligned structural missing date/time values.
2. **Database Schema & Management (PostgreSQL / SQL):**
   - Implemented relational data schemas and executed optimized aggregation queries to extract metrics before visual staging.
3. **Advanced Data Modeling (Power BI Star-Schema):**
   - Rather than keeping simple independent sheets, I established a robust **Star-schema relational model** connecting the **Transaction Fact table** directly with the **Customer Dimension table** via unique identifier keys. This design ensures highly optimized cross-filtering performance.

## 📈 Executive Analytics & Multi-Page UX Layout
The interactive application is structurally divided to serve different stakeholder needs:
- **High-Level Executive Summary:** An automated "OverView Analysis" dashboard monitoring core global KPIs like Total Amount ($137.34M), Total Transactions (15.03K), Avg Transaction Value ($9.12K), Fees ($216.93K), and Regional/Demographic trends.
- **Granular Transaction Details:** A dedicated "Transactions" drill-down view containing comprehensive tabular listings for audit and deep risk verification.
- **Dynamic Controls:** Integrated multi-dimensional filtering panels for Year, Dynamic Metrics, Occupation, and Segment Categories.

## 🛠️ Tech Stack & Tools Used
- **Data Engineering & Querying:** Python (Pandas), SQL (PostgreSQL)
- **Data Modeling & Visualization:** Microsoft Power BI Desktop
- **Project Documentation:** Business Requirement Engineering 

## 📁 Repository Structure & Upload Checklist
To replicate this pipeline, upload the following files to your repository:
- `README.md` - (This documentation file)
- `2nd_working.pbix` - The main Power BI modeling and multi-page visual layout file.
- `Business Requirements.docx` - Original corporate project specifications and requirements framework.
- `customers.xlsx` - Customer dimension database table profile.
- `finance_transactions.xlsx` - Primary financial transactions fact master database table.
- `/png images` - Folder containing dashboard interface screenshots used for portfolio presentations.

## 🚀 How to view the Dashboard
1. Download the `2nd_working.pbix` model from this repository.
2. Open the file with **Power BI Desktop**.
3. Use `Ctrl + Click` to interactively trigger the custom page navigation buttons on the left panel!

---
*Built by an aspiring Data Analyst | Portfolio Project Validation Framework.*

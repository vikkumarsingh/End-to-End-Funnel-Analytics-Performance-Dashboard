# End-to-End Funnel Analytics & Performance Dashboard

An advanced data analytics dashboard, robust DAX implementation, and SQL query suite built to track marketing acquisition, lead progression funnels, and agent call center efficiency.

---

## 📊 Project Overview
This repository contains a technical assessment replicating a multi-step operational and marketing dashboard using raw datasets (`leads`, `call_logs`, `google_ads_daily`, `meta_ads_daily`, `ga_sessions_daily`).

### Key Deliverables:
1. **15-Step Funnel Dashboard (`.pbix`)**: Integrated with Period-over-Period (PoP) comparisons (Current, Previous Week, Last Month) and D7 moving averages.
2. **Disconnected KPI Dimension Model**: Utilized DAX `SWITCH` logic, `ISINSCOPE`, and `CONTAINSSTRING` for clean, dynamic metric mapping and subtotal management.
3. **Advanced SQL Queries (`.sql`)**: Handled daily call metrics, active agent productivity thresholds, and multi-dimensional cohort analyses.

---

## 🛠️ Tech Stack & Tools
* **Tool**: Microsoft Power BI (DAX, Power Query)
* **Language**: SQL (ANSI-compliant)
* **Modeling**: Star schema architecture featuring a disconnected Date dimension and a custom KPI mapping table.

---

## 📂 Repository Contents
* `Dashboard_Assignment.pbix`: The interactive Power BI dashboard file.
* `sql_queries.sql`: Optimized SQL scripts covering daily logs, agent productivity, and lead-to-disbursal funnels.
* `data_insights_note.pdf`: Summary of data quality treatments and 2 core business insights derived from the data.

---

## 📝 SQL Queries Summary
- **SQL 1**: Computed daily unique leads attempted, total outbound calls, and connected call volumes.
- **SQL 2**: Extracted active agent counts meeting daily high-volume operational thresholds (>10 outbound calls).
- **SQL 3**: Aggregated funnel progression metrics (Qualified, Logged-in, Disbursed) segmented by Lead Creation Month and Consumer Durable (CD) Bucket.

---

## 💡 Key Business Insights
1. **Call Connectivity vs. Agent Capacity:** High call volume days show a slight drop in call connectivity percentages despite high agent log-ins, indicating that optimizing hourly shift alignment could boost connected call rates.
2. **Acquisition Efficiency:** Meta Ads demonstrate a significantly lower Cost Per Lead (CPL) compared to Google Ads while maintaining strong top-of-funnel lead volume, providing a clear optimization path for budget allocation.

---
**Author**: Vikash Kumar Singh

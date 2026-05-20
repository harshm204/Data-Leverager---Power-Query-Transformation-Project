# ⚡ Data Leverager – Power Query Transformation Project

> **A complete end-to-end Power Query transformation project in Power BI**  
> Designed to demonstrate real-world ETL, data cleaning, transformation, merging, profiling, and refresh automation techniques.

---

## 📌 Project Overview

This project showcases how to use **Power Query Editor in Power BI** for:

- Data Extraction
- Data Cleaning
- Data Transformation
- Text & Numeric Operations
- Date Intelligence
- Conditional Logic
- Pivoting & Unpivoting
- Merging & Appending Queries
- Grouping & Aggregation
- Data Profiling
- Dynamic Parameters
- Refresh Automation

The project simulates a practical business workflow involving:

- Monthly Sales Files
- Employee Master Data
- Web-based HTML Data Sources

---

# 🧰 Tools & Technologies

| Tool | Purpose |
|------|----------|
| Power BI | Data Visualization & Modeling |
| Power Query | ETL & Data Transformation |
| Excel Files | Source Data |
| HTML Web Tables | External Data Source |
| M Language | Query Logic |

---

# 🚀 Project Tasks & Requirements

---

# 1️⃣ Data Extraction

### ✔ Load HTML Table from Web
Imported a live HTML table from a web source such as:

- COVID Statistics
- Public Data Tables
---

# 3️⃣ Text Tools

Applied text transformation functions to standardize data.

## Functions Used

| Function | Purpose |
|----------|----------|
| UPPER() | Convert text to uppercase |
| LOWER() | Convert text to lowercase |
| TRIM() | Remove extra spaces |
| CLEAN() | Remove non-printable characters |
| REPLACE() | Replace unwanted text |
| Split Column by Delimiter | Separate text fields |

### Use Cases

- Customer Name Cleaning
- Address Standardization
- String Formatting

---

# 4️⃣ Numeric Tools

Implemented numeric transformations including:

- Revenue rounding to 2 decimals
- Profit calculation

---

# 5️⃣ Date & Time Tools

Created advanced date intelligence columns.

## Features Implemented

- Extracted:
  - Day
  - Month
  - Year
  - Quarter

- Created:
  - Fiscal Month
  - Age Calculation

---

# 6️⃣ Conditional Columns & Indexing

Created custom business logic using conditional columns.

## Sales Category Logic

| Category | Condition |
|----------|------------|
| High | ≥ 10,000 |
| Medium | 5,000 – 9,999 |
| Low | < 5,000 |

### Indexing

Added:

- 0-Based Index
- 1-Based Index

---

# 7️⃣ Pivoting & Unpivoting

Performed reshaping operations.

## ✔ Pivot
Converted monthly sales columns into summarized format.

## ✔ Unpivot
Normalized data back into analytical structure.

---

# 8️⃣ Merging & Appending

## Merge Queries

Merged:

- Sales Data
- Employee Data

using:

- Region
- EmployeeID

## Append Queries

Combined monthly sales datasets into a single table.

---

# 9️⃣ Grouping & Aggregation

Grouped data by region and calculated:

- Total Sales
- Average Order Value
- Transaction Count

---

# 🔟 Data Profiling & Quality

Used Power Query profiling tools to analyze data quality.

## Features Used

- Column Profile
- Column Distribution
- Column Quality

## Insights Generated

- Missing Values
- Errors
- Distinct Values
- Unique Counts

---

# 1️⃣1️⃣ Source Settings & Parameters

Implemented dynamic and reusable query logic.

## Features

- Dynamic Folder Path Parameters
- Data Source Credential Management

### Benefits

- Easier Maintenance
- Faster Refresh
- Better Scalability

---

# 1️⃣2️⃣ Refresh Simulation

Simulated real-world refresh automation.

## Scenario

Added a new file:

```bash
Sales_Apr.xlsx
```

and verified:

- Auto-load behavior
- Transformation continuity
- Refresh stability

---

# 📊 Key Learnings

This project demonstrates practical experience with:

- ETL Workflows
- Power Query Transformations
- Data Cleaning Techniques
- Query Optimization
- Business Logic Implementation
- Automated Refresh Processes
- Real-world Data Preparation

---

# 🎯 Business Value

The workflow helps organizations:

- Improve data consistency
- Reduce manual effort
- Automate reporting pipelines
- Enable scalable analytics
- Build reusable ETL processes

---

# 📸 Project Highlights

✅ Folder-Based Data Automation  
✅ Dynamic Query Parameters  
✅ Data Profiling & Validation  
✅ Advanced Power Query Techniques  
✅ Real-world ETL Simulation  

---

# 🧠 Skills Demonstrated

- Power BI
- Power Query
- ETL Development
- Data Cleaning
- Data Transformation
- Data Modeling
- Query Optimization
- Business Intelligence

---

# 📌 Future Enhancements

- Add Incremental Refresh
- Integrate SQL Database
- Create Dashboard Visualizations
- Publish to Power BI Service
- Add Scheduled Refresh

---

# ⭐ If You Like This Project

Give it a ⭐ on GitHub and share your feedback!

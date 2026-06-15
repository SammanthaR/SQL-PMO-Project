SQL PMO Project – Portfolio Management Database

This project demonstrates end‑to‑end SQL skills using a realistic Project Management Office (PMO) dataset.
It includes database design, DDL, DML, indexing, and analytical SQL queries used for portfolio reporting.

Project Structure

sql-pmo-project/
│
├── data/                # Raw CSV files exported from Excel
│
├── ddl/                 # Database schema (DDL)
│   ├── create_tables.sql
│   ├── constraints.sql
│   └── indexes.sql
│
├── dml/                 # Insert scripts (DML)
│   ├── insert_projects.sql
│   ├── insert_resources.sql
│   ├── insert_allocations.sql
│   ├── insert_financials.sql
│   └── insert_health_snapshot.sql
│
└── analytics/           # Analytical SQL queries
    ├── project_health_queries.sql
    ├── financial_variance_queries.sql
    ├── resource_capacity_queries.sql
    ├── portfolio_summary_queries.sql
    └── rag_trend_queries.sql

Database Schema Overview

The database contains five core tables:

    Projects – project metadata, budgets, dates, status

    Resources – employees and contractors

    Project_Resource_Allocation – monthly FTE allocation

    Project_Financials – planned vs actual cost & benefit

    Project_Health_Snapshot – RAG status over time

These tables form a realistic PMO relational model suitable for analytics.

SQL Skills Demonstrated

    Database design & normalization

    DDL: table creation, constraints, indexing

    DML: bulk insert scripts

Analytical SQL:

    joins

    CTEs

    window functions

    aggregations

    trend analysis

    Portfolio reporting queries

How to Run This Project

1. Run all scripts in ddl/ in this order:

    create_tables.sql

    constraints.sql

    indexes.sql
   


2. Load data using the scripts in dml/.
   


3. Execute queries in analytics/ to generate insights such as:

    Project RAG trends

    Budget vs actual variance

    Resource over‑allocation

    Portfolio summaries

Example Insights

    Projects behind schedule

    Cost variance by month

    Resource utilization by department

    Repeated red‑status projects

    Portfolio burn rate


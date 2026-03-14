# Personal Finance BI Solution

This project aims to build a comprehensive Business Intelligence (BI) solution for personal finance. The solution will enable users to analyze market trends, stock Open-High-Low-Close (OHLC) data, time series, fundamental market data, and reference data, all modeled with a star schema and visualized in Power BI or other BI/dashboard technologies.

---

## Project Overview

- **Objective:**  
  To provide a unified analytics platform for personal finance and market insights using robust data modeling and visualization tools.

- **Key Features:**  
  - Integration of market and personal finance data sources (APIs, files, manual uploads)  
  - Data warehouse using a star schema (fact and dimension tables)  
  - Automated ETL/ELT pipelines for regular data ingestion and transformation  
  - Dashboards and reports using Power BI or other BI/visualization technologies (e.g., Tableau, Looker, Apache Superset, Metabase) or custom web dashboards (React/D3, Streamlit, Dash) for intuitive reporting and analytics

---

## Solution Architecture

1. **Data Sources:**  
   - Stock OHLC data (e.g., Yahoo Finance, Alpha Vantage)  
   - Market indices and trends  
   - Fundamental and reference data (e.g., company info)  
   - Personal finance data (bank, investment accounts)

2. **Data Modeling:**  
   - Star schema design with fact tables (transactions, OHLC) and dimension tables (date, stock, account, sector, etc.)

3. **ETL Pipelines:**  
   - Scripts and workflows to collect, clean, and load data into the warehouse

4. **Analytics & Visualization:**  
   - Connect Power BI or any other BI/visualization tool (Tableau, Superset, Metabase, custom web dashboards) to the data warehouse for building dashboards and reports

---

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sdutta055/finbi.git
   cd finbi
   ```

2. **Set up your environment:**  
   - Configure API keys and credentials for your data sources (see `.env.example`)  
   - Install required dependencies for ETL scripts (Python, SQL, etc.)

3. **Run ETL pipelines:**  
   - Follow instructions in the `/etl` folder to fetch and load data

4. **Connect a BI tool:**  
   - Use Power BI Desktop/Service, Tableau, or another BI/visualization tool, or connect a custom dashboard (Streamlit, Dash, React/D3) to your data warehouse and import the data model. Dashboard files in `/dashboards` can be opened with their respective tools.

---

## Project Structure

```
finbi/
├── etl/              # ETL/ELT scripts and workflows
├── data_model/       # Star schema, ER diagrams, and SQL definitions
├── dashboards/       # Dashboard files and templates (Power BI, Tableau, or other visualization/web technologies)
├── docs/             # Documentation and guides
├── .env.example      # Example environment variables
└── README.md
```

---

## Progress & Tracking

Project progress is tracked via [GitHub issues](https://github.com/sdutta055/finbi/issues) and linked boards. Major milestones include:

- Requirements gathering
- Data source integration
- Data warehouse/star schema design
- ETL/ELT pipeline setup
- Dashboard development (Power BI or other visualization tools)
- Testing and documentation

See the issues and TODO board for detailed tasks.

---

## Contributing

Contributions are welcome! Please review the open issues and feel free to submit pull requests or suggestions.

---

## License

This project is licensed under the MIT License.

---
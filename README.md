## Real Estate Data Pipeline: Extraction to PostgreSQL

### Project Overview
This project demonstrates an end-to-end data engineering pipeline that extracts real estate property data from a public API, \
performs exploratory data analysis and transformation, and loads it into a PostgreSQL database using a dimensional model. \
The project ensures data quality, scalability, and a clean structure for analytical consumption.

### Problem Statement
Mars Real Estate is expanding its operations and aiming to make data a central part of its property investment strategy. However, the company faced a major challenge: property data was coming from various third-party sources in unstructured and inconsistent formats, making it difficult to evaluate market trends, assess property values, and support strategic decision-making.

To overcome this, Mars Real Estate needed a robust data pipeline that could reliably extract large volumes of real estate data, clean and organize it, and store it in a structured, analysis-ready format. The goal was to lay the groundwork for advanced analytics and business intelligence tools that would empower agents, analysts, and executives to make faster, smarter decisions across the organization.

### Project Scope
- Extract property listings from RentCast’s API.
- Perform data cleaning and handle missing values.
- Design and implement a dimensional model (star schema).
- Create schema and tables in PostgreSQL using psycopg2.
- Load transformed data into PostgreSQL tables.
- Use GitHub for version control.

## Data Modelling 
![alt text](https://github.com/uchy4life/Mars_realtor/blob/main/databasemodel.png)

![alt text](https://github.com/uchy4life/Mars_realtor/blob/main/ERD_Mars_realtor.png)

### Outcomes
- Successfully transformed and normalized raw property data.
- Built and populated a star schema in PostgreSQL.
- Improved data readiness for BI tools or SQL-based analysis.

### Tech Stack
- Languages & Libraries: Python, pandas, requests, psycopg2, json
- Database: PostgreSQL
- Tools: GitHub Desktop, pgAdmin
- API: RentCast Property API

### Summary
This project reflects proficiency in designing data pipelines from API to data warehouse. \
It covers essential concepts in ETL, dimensional modeling, data cleaning, and relational database management. \
The final PostgreSQL database provides a foundation for further real estate analytics, such as price trend analysis, property type distribution, or location-based filtering.

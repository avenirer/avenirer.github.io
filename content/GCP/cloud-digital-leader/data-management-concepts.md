---
title: 04. Data Management Concepts
---
The list of options when managing vast volumes of data:
- databases
- warehouses
- data lakes

## Databases
A database is an organized collection of data stored in tables and accessed electronically from a computer system.
### Relational databases
A relational database stores and provides access to **data points that are related to one another** (storing information in tables, rows, and columns that have a clearly defined schema that represents the structure or logical configuration of the database).
Relational databases are highly consistent, reliable, and best suited for dealing with large amounts of structured data.
**Google Cloud** relational database products include **Cloud SQL** and **Spanner**.
### Non-relational databases
A non-relational database, sometimes known as a NoSQL database, is less structured in format and doesn’t use a tabular format of rows and columns like relational databases.
Non-relational databases follow a flexible data model, which makes them ideal for storing data that changes its organization frequently or for applications that handle diverse types of data.
**Bigtable** is a non-relational database product.
## Data Warehouses
While a database is designed to capture data for storage, retrieval, and use, a **data warehouse** is designed to **analyze data**.
Think of the data warehouse as the central hub for all business data.
**BigQuery** is Google Cloud's data warehouse offering.
Although data warehouses handle structured and semi-structured data, they’re not typically the answer for how to handle large amounts of available unstructured data, like images, videos, and documents.
## Data Lakes
A data lake is a repository designed to ingest, store, explore, process, and analyze any type or volume of raw data, regardless of the source, like operational systems, web sources, social media, or Internet of Things, or IoT.
It can store different types of data in its original format; ignoring size limits, and without much pre-processing or adding structure.
Having this unprocessed, raw data available for analysis prevents unintentionally contaminating the data or adding bias.

# Data Governance
Data governance means setting internal standards—data policies—that apply to how data is gathered, stored, processed, and disposed of.
Through data governance, users throughout an organization get the data they need to reach and service customers, design and improve products and services, and seize opportunities for new revenues.
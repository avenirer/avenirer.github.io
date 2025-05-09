---
title: 05. Google Cloud Data Management Solutions
---
# Cloud Storage
Cloud Storage offers developers and IT organizations durable and highly available object storage. Object storage is a computer data storage architecture that manages data as “objects” instead of as file.
This type of data is referred to as unstructured, which means that it doesn’t have a predefined data model or isn’t organized in a predefined manner, as you might find in a structured database format.
There are four primary storage classes in Cloud Storage:
- Standard Storage (hot data)
- Nearline Storage (once per month)
- Coldline Storage (once every 90 days)
- Archive Storage (once a year)
Cloud Storage provides a feature called Autoclass, which automatically transitions objects to appropriate storage classes based on each object's access pattern. The feature moves data that is not accessed to colder storage classes to reduce storage cost and moves data that is accessed to Standard storage to optimize future accesses.
# Cloud SQL
Cloud SQL offers fully managed relational databases, including MySQL, PostgreSQL, and SQL Server as a service.
It’s designed to transfer mundane—but necessary and often time-consuming—tasks to Google, like applying patches and updates, managing backups, and configuring replications.
Cloud SQL is the best SQL-based storage option for a transactional workload that requires local or regional scalability.
# Spanner
Spanner is a fully managed, mission-critical, relational database service that **scales horizontally** to handle unexpected business spikes.
Spanner is especially suited for applications that require a SQL relational database management system with joins and secondary indexes, built-in high availability, which provides **data redundancy** to reduce downtime when a zone or instance becomes unavailable (the goal is to prevent a single point of failure), strong **global consistency**, which ensures that all locations where data is stored are updated to the most recent data version quickly, and high numbers of input and output operations per second (tens of thousands of reads and writes per second or more).
# BigQuery
BigQuery is a fully-managed data warehouse. BigQuery provides two services in one: **storage** and **analytics**.
Data in BigQuery is encrypted at rest by default without any action required from a user.
BigQuery works in a multicloud environment, which lets data teams eradicate data silos by using BigQuery to securely and cost effectively analyze data across multiple cloud providers.
BigQuery also has built-in machine learning features so that ML models can be written directly in BigQuery by using SQL.
# Firestore
Firestore is a flexible, horizontally scalable, NoSQL cloud database for storing and syncing data in real-time.
Firestore can be directly accessed by mobile and web applications.
Firestore performs data storage in the form of documents, with the documents being stored in collections.
It’s been designed to scale automatically depending on user demand, but retains the same level of performance irrespective of database size.
Firestore also provides offline usage through a comprehensive database on users’ devices.
# Bigtable
Bigtable is designed to handle large workloads at consistent low latency, which means Bigtable responds to requests quickly, and high throughput, which means it can send and receive large amounts of data.
For this reason, it's a great choice for both operational and analytical applications, including Internet of Things, user analytics, and financial data analysis.
When deciding on a storage option, you might choose Bigtable if you’re working with more than 1TB of semi-structured or structured data, data is fast with high throughput, or it’s rapidly changing, you’re working with NoSQL data, data is a time-series or has natural ordering, you’re working with big data and running batch or real-time processing on the data, or you’re running machine learning algorithms on the data.
# Conclusions
If data is unstructured, then Cloud Storage is the most appropriate option.
**Google Cloud’s Database Migration Service (DMS)** can easily migrate your databases to Google Cloud, or **Datastream** can be used to synchronize data across databases, storage systems, and applications.

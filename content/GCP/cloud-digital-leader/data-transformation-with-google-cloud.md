---
title: 07. Data transformation with Google Cloud
---
**Streaming analytics** is the processing and analyzing of data records continuously instead of in batches.
Generally, streaming analytics is useful for the types of data sources that send data in small sizes, often in kilobytes, in a continuous flow as the data is generated.
This results in the analysis and reporting of events as they happen.
Companies use streaming analytics to analyze data in real time and provide insights into a wide range of activities, such as metering, server activity, geolocation of devices, or website clicks.
**Google Cloud offers two main streaming analytics products** to ingest, process, and analyze event streams in real time, which makes data more useful and accessible from the instant it’s generated:
- Pub/Sub
- Dataflow

# Pub/Sub
**Pub/Sub** is a distributed messaging service that can receive messages from various device streams such as gaming events, IoT devices, and application streams.
The name is short for **Publisher/Subscriber**, or publish messages to subscribers.
# Dataflow
After messages have been captured from the streaming input sources you need a way to pipe that data into a data warehouse for analysis. This is where Dataflow comes in.
Dataflow creates a pipeline to process both streaming data and batch data.
“Process” in this case refers to the steps to extract, transform, and load data, sometimes referred to as ETL.
A popular solution for pipeline design is **Apache Beam**.  
Dataflow is serverless and fully managed. Google Cloud manages infrastructure tasks on behalf of the users, like resource provisioning, performance tuning, and ensuring pipeline reliability.
---
title: 02. AWS global infrastructure
---

Storing files on an AWS server, we have access to it from anywhere. AWS is prepared for any accidents on Data centers, having redundancy. Same information is saved on multiple data centers.

Multiple data centers are grouped in a cluster called **Availability Zone (AZ)**. The AZs also have redundancy, being connected with redudant high speed and low latency links.

Multiple AZs are also in a cluster called **Region**.

## Considerations to take when selecting a region

- **compliance** - some applications, companies, countries require that your data must be handled in a specific way.
- **latency** - make sure your IT resources are close to your user base for a faster response time
- **pricing** - depending on the different tax structures, some regions might cost more/less than others.
- **service availability** - some services you need might not have been activated on specific Regions, right away, so you might find yourself needing to select a region that has specific service available.

## Global Edge Network

Consists of **edge locations** and **regional edge caches** which are used to cache content closer to end users, reducing latency. These can be used to cache frequently accessed content. **[[cloudfront.md | Amazon CloudFront]]** can be used to cache content using edge locations.

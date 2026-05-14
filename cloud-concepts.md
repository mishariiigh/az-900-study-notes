# Cloud Concepts

## What is Cloud Computing?
Cloud computing is the delivery of computing services over the internet, including servers, storage, databases, networking, and software.

## Cloud Models

### IaaS (Infrastructure as a Service)
- Provides virtual machines and networking
- User manages OS and applications
- provide on demands, virtualization computing, storage and networking resources hosted in Microsoft data centers.
- it enables businesses to migrate, develop, and scale applications by renting infrastructure rather than maintainning physical hardware, reducing capital expenditures and supporting a pay-as-you-go model.
* Azure virtual machine (VMs): offers secure, vertualized server instances for Windows or Linux, supporting rapid deployment for apps and workloads.
* Azure virtual network (VNet): Connects VMs to each other, to the internet, and to on-premises data centers securly.
* Azure storage: provides highly scalable and secure object storage for data, including disks for VMs, file storage, and blobs. 
* Azure Load Balancer: Distributes traffic across VMs to improve application performance and relibility.

#### Key advantage of Azure IaaS
- Reduced costs: eliminates the expense of purchasing and maintaining physical, on-premise hardware.
- Flexible Scaling: instantly scale infrastructure up or down to meet fluctuating demand, paying only for used resources.
- Enhanced Security: Features built-in, multi-layered security to protect workloads from the silicon to the cloud.
- Business Continuity: offers high availibility and disaster recovery solutions to keep applications running during distruption.

#### Common Use Cases
- lift-and-shift Migration: Moving existing applications to the cloudwith minimal changes.
- development & testing: Rapidly creating and tearing down test enviroments.
- Storage & backups: storing large datasets and managing data recovery withoutm maintaining physical servers.

#### Responsibility Model
With Azure IaaS, Microsoft manages the physical data center, servers, and networking hardware. users are responsible for configuring, patching and maintaining the operationg system, middleware, and application software running on those machines.

### PaaS (Platform as a Service)
- Provides platform to deploy apps without managing infrastructure
- Azure Platform as a service (PaaS) offersa fully managed enviroment for building, testing, and deploying applications without managing underlying servers, storage or networking. Ket services include Azure App service, Azure SQL, and Azure Functions which provide automatic scaling, patching, and built-in integration for CI/CD, allowing developers to focus solely on code

#### Core Characterstics of Azure PaaS
- No Infrastructure Management: Microsoft handles operating system, middleware, and runtime updates.
- scalability & High Availibility: Resources can be automatically scaled up or down based on demand.
- Developer Focus: Streamlines app lifecycles with built-in development  tools, CI/CD, pipelines, and SDK.
- Security & Compliance: offers built-in identity management, encryption and threat detection.

#### Key Azure PaaS offerings.
- compute Azure Apps Service for web/mobile apps, Azure Functions for serverless code.
- Databases: Azure SQL Database(Fully managed relational database) and Cosmos DB(NoSQL).
- Analytical & Integration: Azure Data Factory for ETL Workflows and API Management.

#### Advantage of Azure PaaS.
- Fast Time to Market: Ready-to-use enviroments speed up development.
- Cost Effciency: Pay-as-you-go model reduces infrastructure overhead costs.
- Reduced Complexity: Simplifies development by handling pathcing, backups, and  runtime updates.

#### Networking & Security
- identity Based Security: Modern Azure PaaS relies on strong authentication (e.g., Azure AD) rather than relying only on traditional network perimeters.
- Private Connectivity: Azure Private Link and Service Endpoints allow secured access to PaaS services within virtual networks.


### SaaS (Software as a Service)
- Fully managed applications delivered over the internet

## Cloud Types

- Public Cloud (Azure, AWS)
- Private Cloud
- Hybrid Cloud

## Key Benefits
- Scalability
- High availability
- Cost efficiency
- Global reach
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
- Sofware as a Service (SaaS) on Azure is a cloud-based model delivering fully  functional sofware  applications over the internet on a subscription basis, with Microsoft Azure handling all infrstructure, security and maintenance. it eliminates local installation, providing scalable, ready-to-use tools like Microsoft365 Dynamics 365, and AI services.

#### Key Features of Azure SaaS
- Ready-to-Use: Applications are fully  developed and accessible via web browser or APIs.
- Management by Provider: Azure manages the underlying infrastructuer, middleware, and application data, requiring no mainenanace from the end-user.
- Subscription-Based: pricing is usually  on a monthly or annual subscription, often based on user count or feature usage.
- Multitency: A single instance of the software serves multiple customers, which optimize resources and lowers costs.
- Scalability: Users can easily adjust subscriptions to scale up or down as needed.

#### Common SaaS Examples in Azure
- Microsoft 365: office prodictivity apps (Word, Excel) and email services.
- Dynamic 365: Customer relational management (CRM) and ERP solutions.
- Azure AI Services: Tools for language processing, speech, vision, and decision-making.
- Power BI: Data analytics and visualization tools.

#### Azure SaaS vs PaaS vs IaaS
- SaaS (Software as a Service): Azure manages everything (Application, Data, Runtime, Middleware, OS, Virtualization, Servers, Storage, Networking)
- PaaS(Platform as a Service): You manage applications and data; Azure manages runtime, middleware, and infrastructure.
- IaaS (Infrastructure as a Service): You manage OS, middleware, runtime, data, and applications; Azure manages servers and storage.

#### Delivering SaaS on Azure
- For developers building their own  SaaS applications, Azure provides specialized resources to artchitect multitenant sulotions, unsuring secure and scalable delivery. Developers can also list their SaaS applications on the Azure Marketplace for global reach, as outlined in this guide to listing your app.

#### Benefits:
- Reduced Costs: Lower upfront costs and no hardware maintenance fees.
- Automatic Updates: Always access the latest version with security patches, handled by Azure.
- Accessibility & Mobility: Access applications from any device with an internet connection

## Cloud Types

- Public Cloud (Azure, AWS)
- Private Cloud
- Hybrid Cloud

Azure cloud types are categorized by deployment (how resources are hosted) and service models (what is managed). The primary deployment models include <b>Public</b>, <b>Private</b> and <b>Hybrid</b> clouds. Azure as public cloud, offers services on a pay-as-you-go basis, providing scalability and flexibility, with options for on-premsis extensions.

these defines how and where your  cloud infrastructure is hosted:
- Public Cloud (e.g., Azure): Resources are owned and managed by Microsoft shared among many organization over the internet. It offers high scalability and cost efficiency, as you pay only for what you use.
- Private Cloud: Services are dedicated exclusively to a single organization, often managed on-premises or by a third party. It offers maximum control and security, making it suitable for sensitive data.
- Hybrid Cloud: Combines public and private clouds, allowing data and appliactions to move between them. this provides flexibility, enabling organizations to use Azure Stack for on-premises workloads while accessing public cloud scalability.
- Multi-cloud: Uses multiple public cloud provides simultaneously(e.g., Azure + AWS) to optimize workloads or avoid vendor lock-in.

#### Azure Cloud Service Models
These defines the division of responsibility for managing  technology:
- Infrastructure as a Service (IaaS): Rents raw IT infrastructure - virtual machines (VMs), storage, networks from Azure, providing the most control.
- Platform as a Service (PaaS): Provides a managed enviroment for developing, testing, and deploying application without managing the underlying  infrastructure.
- Software as a Service (SaaS): Delviers fully managed software application over the internet on a subscription basis such as Microsoft 365.
- Serverless Computing: A specialized form of PaaS where developers write code, and Azure manages all infrastructure required to run it, automatically scalling based on demand.

#### Key Azure Features and Advantages
- Scalability & Flexibility: Reasources can be scaled up or down instantly.
- Cost Management: Pay-as-you-go pricing ensures you only  pay for reasources utilized.
- Security: Built on a secure, hardened Infrastructure with extensive compliance certifications.
- Wide product Portfolio: Access Azure Products ranging from AI + Machine learning, Databases, Compute, and Containers.


## Key Benefits
### Scalability
- Azure Scalability allows resources to adapt capacity to meet demand, ensuring performance during high traffic while optimization costs. it includes vertical scalling (upgrading capacity) and horizantal scalling (adding instances), with Autoscalling tools that automatically adjust to workload fluctuations. Key Services include App Service, Azure Funcations and Virtual Machine Scale Sets.
#### Key Scalability types in Azure
- Scale Up/Down (Vertical Scalling): Increasing or decreasing resources (CPU, RAM) of a single instance, such as changing Virtual Machine size. This is used when the application cannot be distributed across multiple instances.
- Scale Out/In (Horizantal Scalling): Adding or removing instances of resources, such as virtual machines or containers instances. this is ideal for cloud-native apps and enables high availability.
-Autoscalling: Automatically adjusts resources based on telemetry data (e.g., CPU usage) or schedueles. This provides elasticity, reducing cost when traffic is low.
#### Core Azure Srives and Scaling Features
- Azure App Services: Offers "Scale up" (tier changes) and "Scale out" (instance count) options  in the portal.
- Virtual Machine Scale Sets: Enables Creating and Managing group of identical, load-balanced VMs that can automatically scale in or out.
- Azure Functions: Features event-driven scalling, where the scale controller adds more instances to handle incoming events automatically.
- Azure SQL Database: Supports  event-driven scalling, where the scale controller adds more instances to handle incoming events automatically.
- Azure Storage: Features automatic scalling for storage accounts to handle high performance and capacity demands.

#### Best Practice for Scalability.
- Design for Horizantal Scalling: Create applications that can distribute load across instancess.
- Use Azure Monitor: Monitor key performance metrics to trigger scalling actions.
- Implement Caching: Use services like Azure Cache for Redis to reduce backened database load.
- Partitioning Data: Use technique like shrading to ditribute large datasets, improving performance and scalability.

#### Differences in Azure Scaling
- Scaling vs. Elasticity: <b>Scalability</b> is the ability to handle increased load; <b>elasticity</b> is the ability to automatically handle that increase in real-time.
- Scale up vs Scale out: Microsoft Azure clarifies that Scalling up adds resources to an existing server, while scalling out adds more servers.


### High availability
- High Availibility (HA) In Microsoft Azure ensures your applications and data remain continuously accessible despite component failures of schdueled maintenance. Azure achieves this by offering a global infrastructure with redundant hardware, autmated failover, and geographically distributed resources.

#### 1. Azure Global infrastructure & Redundancy
- At the core of Azure's high availibility are its  deplotment architectures:

* Availibility Zones (AZs): Physically separated locations within an Azure region, each equipped with independent power, cooling, and networking. deploying multi-tiered applications across AZs protects you from localized datacenter failures.

* Regain Pairs: Azure Pairs regions within same geograph (eg. Canada Central and Canada East) to provide reliable disaster recovery  by automatically replicating underlying storage and services.

#### 2. Built-in Compute & Storage Reliability
* Availibility Sets: For older or specific Virtual Machine (VM) deployments, availibility sets spread VMs accorss different fault domain (separate hardware racks/power sources) and update domains (separate schdueled maintenance windows) to gurantee a 99.5% uptime SLA.

* Managed Disks: Azure Managed Disks automatically replicate data three times within a single region, providing 99.99999% durability and protecting againste drive or node failures.

#### 3. Service-Specific HA Mechanisms
- Azure natively supports automated failover and replica distruption for PaaS (Platform as a Service) offering :
* Databases: Services like Azure SQL Database, PostgreSQL, and MySQL deploy standby replicas. They use zone-redundant or local-redundant high availibility to ensure transactions continue even if a replica fails.

* Gloabal Load Balancing: Tools such as Azure Load Balancer, Azure Application Gateway, and Azure Front Door help route traffic away from unhealthy or unreachable resources, guranteeing a seamless user experience.

#### 4. SLA Guarantees 
- Micorsoft gurantees varying Service Level Agreements (SLAs) based on your architechture:
* Single VM (Premium Storage): 99.9%
* Multiple VMs in an Availibility set: 99.95%
* Multiple VMs across Availivility Zones: 99.9%

#### Practical Next Steps:
To build highly availible architechture, it is curcial to understand the foundational stategies and checklists for maintaining resiliant systems. 
more to read to understand basic building blocks and principles (<a href="https://blobeater.blog/2022/05/31/azure-high-availability/">Azure High Availibility</a>)
### Cost efficiency

- Azure cost effciency is a continuos process of aligning cloud spend with business value. It leverages consumption-based pricing, advanced discounts, and built-in management tools to eliminate waste and maximize your return on investment.

#### 1. Core Pricing Models.
* Pay-as-you-go: Billed for exact usage (per second, minute, or gigbytes) with no up-front commitments.
* Azure Reservations: Pre-commit to 1- or 3-year usage for stable workloads to save up to 72%.
* Azure Service Plan: A flexible pay-as-you-go commitment across compute service to save up to 65%.
* Azure Hybrid Benefit: Use on-premises Winsows Server SQL, SQL Server, or Linux subscriptions with active Software Assurance to heavily discount Azure VMs and SQL databases.

#### 2. Built-in Cost Optimization Tools
* Azure Cost Management + Bilings: Track resources usage, identifiy cost drivers, set budgets, and generate alerts when spending approaches limits.
* Azure Advisor: Analyzes your configurations and provide personlaized recommendations for high-usage resources, right-sizing(downgrading oversized VMs) and leveraging idle resources.

#### 3. Actionable Best Practices
* Right-sizing: Review metrics and downgrade Virtual Machines (VMs) or databses that are consistently underutilized.
* Auto-scaling: Utilize VM Scale Sets and serverless fucntions (like Azure Functions) to automatically provision capacity during demand spikes and scale down during off-hours.
* Resources Schdueling: Implement automated scripts or policies to shut down non-production (e.g, Development/Testing) enviroments at night and over weekends.
* Data Tiering: Move inactive or older data from expensive hot storage to cooler Azure Blob Stroage or Archive tiers.

#### 4. Strategic Cloud Design
* Workload Isolation: Distinguish between production and non-production enviroments, pre-production enviroments rarely need production-level resiliance, logging, or scale, and can  use cheaper VM SKUs.
* Cost Guardrails: Apply Azure Policies and resource group budgets to prevent unapproved or incidental charges from occuring in the first place.

- Global reach
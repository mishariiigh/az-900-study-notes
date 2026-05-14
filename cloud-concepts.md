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
- Scalability
- High availability
- Cost efficiency
- Global reach
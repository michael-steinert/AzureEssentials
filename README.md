# Azure Essentials

## Cloud Computing

- Cloud Computing is the Provision of IT Services over the Internet
- Computing Services include general IT Infrastructure such as Virtual Computers, Storage, Databases and Networks
- Cloud Services also extend traditional IT offerings with Capabilities such as the Internet of Things (IoT), Machine Learning (ML) and Artificial Intelligence (AI)
- Cloud Computing is not constrained by the physical Infrastructure of a traditional Data Centre because it uses the Internet to deliver these Services

## Shared Responsibility

- With Shared Responsibility, Responsibilities are divided between the Cloud Provider and the User
- The Cloud Provider is responsible for the physical Security, Power Supply, Cooling and Network Connection
- The User is responsible for the Data and Information stored in the Cloud
- The User is also responsible for Access Security, i.e. ensuring that only those who need Access are granted Access
- Shared Responsibility is associated with the following Types of Cloud Services: Infrastructure as a Service (IaaS), Platform as a Service (PaaS) and Software as a Service (SaaS)
- With IaaS, most of the Responsibility lies with the User, with the Cloud Provider responsible for basic physical Security, Power and Connectivity
- With SaaS, most of the Responsibility lies with the Cloud Provider
- PaaS is in between IaaS and SaaS and distributes the Responsibility equally between the Cloud Provider and the User

<p align="center">
  <img src="https://github.com/michael-steinert/KubernetesEssentials/assets/29623199/82b20636-68ed-4937-84a1-9f2c0ad9d6c1" alt="Shared Responsibility" width="40%"/>
</P>

### Infrastructure-as-a-Service (IaaS)

- Infrastructure-as-a-Service (IaaS) is the most flexible Category of Cloud Services, as it gives Users the greatest possible Control over their Cloud Resources
- In an IaaS Model, the Cloud Provider is responsible for the Hardware, Network Connectivity and physical Security. The User is responsible for everything else: Installation, Configuration and Maintenance of the Operating System, Network Configuration, Database and Storage Configuration
- IaaS is suitable for the following Scenarios:
  - Lift and Shift Migration: Users set up cloud Resources similar to their local Data Centre and then simply move the System that is running locally to the IaaS Infrastructure to run
  - Test and Development: Users have created Configurations for Development and Test Environments that they need to replicate quickly. With an IaaS Structure, Users can quickly set up or shut down the different Environments while maintaining complete Control

### Platform-as-a-Service (PaaS)

- Platform-as-a-Service (PaaS) is a Middle Ground between Renting Storage Space in a Data Centre (Infrastructure-as-a-Service) and Buying a complete, Deployed Solution (Software-as-a-Service)
- In a PaaS Environment, the Cloud Provider manages the physical Infrastructure, physical Security and Connection to the Internet
- The Cloud Provider is also responsible for Operating Systems, Middleware, Development Tools and Business Intelligence Services that are Part of a Cloud Solution
- In a PaaS Environment, Users do not have to care about Licensing or Patching Operating Systems and Databases
- The PaaS Environment provides Users with a complete Development Environment without having to manage the entire Development Infrastructure
- PaaS is suitable for the following Scenarios:

  - Development Framework: PaaS provides a Framework that Developers can use as a Basis for Developing or Customizing Cloud-based Applications. PaaS enables Developers to create Applications with integrated Software Components. Cloud Features such as Scalability, high Availability and Multi-Instance Capability are included and reduce the Programming Effort for Developers
  - Analytics and Business Intelligence: PaaS Tools allow Companies to extract and analyze their Data to gain Insights, identify Patterns and predict Outcomes. In this Eay, Forecasting, Product Development Decisions, Returns and other Business Decisions can be improved

### Software-as-a-Service (SaaS)

- Software-as-a-Service (SaaS) is a complete Cloud Service Model from a Product Perspective
- With SaaS, Users rent or use a fully developed Application
- The SaaS Model is inflexible but easy to set up and run, requiring little technical Expertise to deploy
- Email Programmes, Financial Software, Messaging Applications and Network Software are Examples of SaaS Implementations

## Cloud Models

- Cloud Models define the Way Cloud Resources are delivered

### Private Cloud

- A Private Cloud is used by a single Company
- Private Clouds offer more Control to the Company and its IT Department
- Private Clouds also incurs higher Costs
- A Private Cloud can be hosted in an on-premises Data Centre or in a dedicated Data Centre

### Public Cloud

- A Public Cloud is created, controlled and managed by a Third-Party Provider
- In a Public Cloud, anyone who wants to purchase Cloud Services can access and use the Resources
- General public Availability is an important Difference between Public and Private Clouds

### Hybrid Cloud

- A Hybrid Cloud is an IT Environment that uses both Public and Private Clouds in an interconnected Environment
- A Hybrid Cloud Environment can be used to provide a Private Cloud for increased, temporary Demand by providing Public Cloud Resources
- A Hybrid Cloud can be used to provide an additional Layer of Security
- For Example, Users can flexibly choose which Services to keep in the Public Cloud and which to provide to their Private Cloud Infrastructure

| Public Cloud                                                       | Private Cloud                                                      | Hybrid Cloud                                                      |
| ------------------------------------------------------------------ | ------------------------------------------------------------------ | ----------------------------------------------------------------- |
| No highly scalable Investment Costs                                | Organizations have full Control over Resources and Security        | Offers the greatest Flexibility                                   |
| Applications can be quickly deployed and decommissioned            | Data is not merged with Data from other Organizations              | Organizations determine where their Applications run              |
| Organizations only pay for what they use                           | Hardware needs to be purchased and maintained for Deployment       | Organizations control Security, Compliance, or Legal Requirements |
| Organizations do not have full Control over Resources and Security | Organizations are responsible for Hardware Maintenance and Renewal |                                                                   |

### Multi-Cloud

- In Multi-Clouds, several Public Cloud Providers are used
- This makes it possible to use different Functions from different Cloud Providers
- `Azure Arc` includes Technologies that help manage a Cloud Environment
- `Azure Arc` can manage a Cloud Environment, whether it is a Public Cloud or an Azure-only Cloud, a Private Cloud, a Hybrid Cloud or even a Multi-Cloud

## Consumption-based Model

- IT infrastructure Models can be compared by two Types of Expenses: Capital Expenditure (CapEx) and Operating Expenditure (OpEx)
- CapEx are one-off Costs incurred upfront to acquire or secure physical Resources
- Examples for CapEx include Constructing a new Building or Setting up a Data Centre
- OpEx are Expenses that are continuously incurred for Services or Products
- Examples for OpEx include Registering for Cloud Services or Using the Consumption-based Cloud Computing
- With Cloud Computing, there are no Costs for the physical Infrastructure, Electricity, Security or other Maintenance Aspects of a Data Centre
- With Cloud Computing, Users only pay for the IT Resources they use
- The Advantages of the Consumption-based Model are:
  - No Upfront Costs allow to plan and manage Operating Costs
  - Costly Infrastructure that may not be fully utilized by Users does not need to be purchased and managed
  - Additional Resources can be purchased as Demand increases
  - The Ability to pay for fewer Resources when fewer are needed

<hr>

## Advantages of Cloud

- The biggest Challenges in Building or Deploying a Cloud Application are Uptime (or Availability) and Demand Processing (or Scaling)
- Reliability and Predictability are also two important Advantages of the Cloud

### High Availability

- When Deploying an Application, Service or any IT Resource, Resource Availability is critical
- High Availability is about ensuring maximum Availability, regardless of Interruptions or possible Events
- `Azure` is a high availability Cloud Environment that includes service-specific Uptime Guarantees
- These Guarantees are part of the Service Level Agreements (SLAs)

### Scalability

- The Scalability of Cloud Resources provides the Ability to match Resources to Demand
- If Systems are overloaded at Peak Times, additional Resources can be added to handle the increasing Amount of Traffic
- Scaling benefits from not overpaying for Services, as the Cloud is a Consumption-based Model, only what is actually consumed is paid for
- There are two Options for Scaling: vertical and horizontal Scaling
  - With Vertical Scaling, Resource Functions are expanded or reduced
  - Horizontal Scaling increases or decreases the Number of Resources

#### Vertical scaling

- If more Computing Power is needed to develop an Application, Vertical Scaling can be used to add CPUs or RAM to the Virtual Computer
- By decreasing the CPU or RAM Specifications, Resources can also be scaled down vertically if it is determined that less Computing Power is needed

#### Horizontal scaling

- Horizontal Scaling allows provisioned Resources to be scaled up (automatically or manually) as Demand increases
- For Example, more VMs or Containers can be added or removed (automatically or manually) when Demand decreases

### Reliability

- Reliability is the Ability of a System to recover from a Failure and remain operational
- It is also one of the Cornerstones of the Microsoft Azure Well-Architected Framework
- The Cloud supports Through its decentralized Design a reliable and resilient Infrastructure
- This decentralized Design of the Cloud enables Resources to be deployed in Regions around the World
- If an Emergency occurs in one Region, the other Regions continue to function thanks to global Scaling
- A Cloud Environment is automatically moved to another Region without Users having to take any Action themselves

### Predictability

- Predictability in the Cloud enables the Prediction of Performance and Cost
- Both Performance and Cost Prediction are heavily influenced by the Microsoft Azure Well-Architected Framework
- When a Solution is deployed based on this Framework, Cost and Performance can be predicted

### Performance

- Performance Prediction focuses on predicting the Resources that need to be provisioned to deliver a positive Customer Experience
- Auto-Scaling, Load Balancing and high Availability are just some of the Cloud Concepts that support Performance Prediction
- When more Resources are needed, Auto-Scaling can provide additional Resources to meet Demand, and when Demand drops again, Resources are scaled down
- If Traffic is heavily concentrated in one Area, Load Balancing can redirect it to less busy Areas of the System

### Cost

- Cost Prediction focuses on Predicting or Forecasting the Cost of Cloud Expenditure
- The Cloud makes it possible to track Resources in Real Time, Monitor Resources to ensure they are being used as efficiently as possible, and apply Data Analytics to identify Patterns and Trends that help better plan Resource Provisioning
- By Operating in the Cloud, Cloud Analytics and the resulting Data, future Costs can be predicted and Resources adjusted as needed

### Governance

- Whether deployed Infrastructure-as-a-Service or Software-as-a-Service, Cloud Capabilities support Governance and Compliance
- Templates ensure that all provisioned Resources comply with Corporate Standards and Regulatory Requirements
- In addition, all provisioned Resources can be updated to meet new Standards following Changes in Standards
- Cloud-based Monitoring flags all Resources that do not comply with Corporate Standards
- In addition, Risk Mitigation Strategies are suggested
- Depending on the Operating Model, Software Patches and Updates can also be applied automatically, which benefits both Governance and Security

### Security

- When maximum Control over Security is important, physical Resources are provided as Part of Infrastructure-as-a-Service
- By Infrastructure-as-a-Service, the Management of the Operating Systems and installed Software, including Patches and Maintenance, remains the Responsibility of the User
- If the user wants patching and maintenance to be automatic, Platform-as-a-Service or Software-as-a-Service may be the best Cloud Strategies for them
- Because the Cloud is designed to deliver IT Resources over the Internet, Cloud Providers can defend against Attacks such as Distributed Denial of Service (DDoS), making the System Network more robust and secure

### Management

- For Cloud Computing, there are the following two types of Manageability

#### Cloud Management

- Cloud Management means managing the Cloud Resources. The following is possible in the Cloud:
  - Automatic Scaling of Resource Provisioning according to Demand
  - Provision Resources based on a pre-configured Template, eliminating the Need for manual Configuration
  - Monitor the Integrity of Resources and automatically replace faulty Resources
  - Receive automatic Alerts based on configured Metrics so the User is informed of Performance in Real Time

#### Management in the Cloud

- Cloud Management is about how the User can manage its Cloud Environment and Resources. The User can manage them in the following Ways:
  - Via a Web Portal
  - Via a Command Line Interface
  - Via APIs

<hr>

## Organizing Structure

- The Organizing Structure for Resources in Azure includes the following four Levels: Management Groups, Subscriptions, Resource Groups, and Resources

<p align="center">
  <img src="https://github.com/michael-steinert/AgileSoftwareDevelopmentDAO/assets/29623199/a5f39b5e-cbd5-45d5-9c53-f5011376c86a" alt="Organizing Structure for Resources" width="25%"/>
</P>

- **Resources**: Resources are Instances of Services created by Users, such as Virtual Computers, Storage, or SQL Databases.
- **Resource Groups**: Resources are grouped together into Resource Groups. Resource Groups act as logical Containers in which Azure Resources such as Web Applications, Databases, and Storage Accounts are deployed and managed
- **Subscriptions**: A Subscription groups together User Accounts and the Resources created by those Accounts. Each Subscription has Limits or Contingents on the Number of Resources that can be created and used. Organizations can use Subscriptions to manage the Costs and Resources created by Users, Teams, or Projects
- **Management Groups**: Management Groups allow Users to manage Access, Policy, and Compliance for multiple Subscriptions. All Subscriptions in a Management Group automatically inherit the Terms that apply to the Management Group

## Region, Availability Zone and Region Pair

- Resources are created in Regions that are different geographic Locations around the World with Azure Data Centers
- Azure consists of Data Centers distributed around the World
- When a User uses a Service or creates a Resource, such as an SQL Database or a Virtual Machine, physical Devices are used in at least one of these Locations
- These dedicated Data Centers are not directly available to Users, because they are organized by Azure into Regions
- These Regions contain Availability Zones, which are separate Azure Data Centers in the respective Region

### Region

- A Region is a geographic Area in the World that contains at least one, but possibly more, Data Centers that are close together and connected by a low-latency Network
- Azure intelligently allocates and controls Resources within each Region to ensure that Workloads are distributed evenly
- Regions enable better Scalability and Redundancy as well as Data Residency for Resources
- Specialized Regions can also be used for Compliance or Legal Reasons

### Availability Zone

- Users assemble their compute, storage, network and data resources in one Availability Zone and can replicate them in other Availability Zones.
- Users create their Compute, Storage, Network and Data resources in an Availability Zone and can replicate them to other Availability Zones
- Availability Zones provide Redundancy of Services and Data to protect them in the event of a Failure, enabling high Availability of an Application
- Availability Zones are physically separate Data Centers in an Azure Region
- Each Availability Zone consists of at least one Data Center whose Power, Cooling, and Network Operations function independently
- Availability Zones are set up as isolation Boundaries, but are interconnected via high speed private Networks
- Availability Zones are provided for Virtual Machines, managed Volumes, Load Balancers and SQL Databases. Therefore they are supported by the following Categories of Azure Services:
  - Zonal Services: They permanently assign the Resource to a specific Zone (e.g. Virtual Machines, managed Volumes or IP Addresses)
  - Zone redundant Services: The Platform automatically replicates across Availability Zones (e.g. Zone-redundant Storage or SQL Database)
  - Non-regional Services: Services are always available in Azure Geographies and are resilient to both Zone-wide and Regional Failures

### Region Pair

- Region Pairs are Regions that are combined with another Region at least 300 miles (approx. 480 km) away within the same Geography (e.g. USA, Europe or Asia)
- Region Pairs enable Replication of Resources within a Geography to reduce the Likelihood of Interruptions due to major Events

<hr>

## Azure Resource

- Before a Subscription can be created, Resources must be created and stored in Resource Groups. These terms are defined as follows:
  - **Resource**: A Resource is a manageable Element that is available through Azure. Examples of Resources include Virtual Machines, Storage Accounts, Web Applications, Databases and Virtual Networks
  - **Resource Group**: A Resource Group is a Container that contains related Resources for an Azure Solution. The Resource Group contains Resources that the User wants to manage as a Group. The User decides which Resources belong to a Resource Group depending on what makes the most Sense for their Organization

<hr>

## Azure Resource Groups

- A Resource Group is a logical Container for Resources that are provisioned in Azure
- Azure Resources include everything the User creates in an Azure Subscription
- All Azure Resources must be in a Resource Group and a Resource can only belong to one Resource Group
- Resource Groups help Users organize and manage their Azure Resources by adding their Resources that are similar in Terms of Use, Type or Location to a Resource Group
- This logical Grouping is important for Users because Azure Resources are stored in an unorganized Way

### Lifecycle

- Deleting a Resource Group deletes all the Resources it contains
- Organizing Resources by Life Cycles can be useful in non-production Environments where Users may run an Experiment and then delete it again
- Resource Groups allow Users to easily delete multiple Resources at once

### Authorization

- Resource Groups can be assigned Permissions as Part of Role-based Access Control (RBAC)
- By Assigning RBAC Permissions to a Resource Group, Users can simplify Administration and limit Access to what is necessary

### Azure Resource Manager

- Azure Resource Manager is the Provisioning and Management Service for Azure
- It provides a Management Layer to create, update and delete Resources in an Azure Account
- Users can use Management Features such as Access Control, Locks and Tags to protect and organize their Resources after Provisioning
- When a User sends a Request via one of the Azure Tools, APIs or SDKs, it is received by Resource Manager, where the Request is authenticated and authorized and then the Resource Manager sends the request to the Azure Service that performs the requested Action
- Since all Requests are processed through the same API, the Results and Functions are consistent across all Tools

<p align="center">
  <img src="https://github.com/michael-steinert/AgileSoftwareDevelopmentDAO/assets/29623199/23097133-64e6-4395-98dc-7c8e3645f8ec" alt="Resource Manager" width="35%"/>
</P>

- The Resource Manager has the following Advantages:

  - Management of Infrastructure via declarative Templates (instead of Scripts). A Resource Manager Template is a JSON File that defines what the User wants to provision in Azure
  - Provision, manage and monitor all Resources for the Azure Solution as a Resource Group, instead of managing these Resources individually
  - Users can redeploy their Azure Solution during the Development Cycle and be confident that their Resources are deployed in a consistent State
  - Define Dependencies between Resources so they are provisioned in the correct Order
  - Apply Access Control to all Services as Role-based Access Control (RBAC) is natively integrated into the Management Platform
  - Apply Tags to Resources to logically organize all Resources in the subscription
  - Provide Billing Information to Users by Displaying the Cost of a Resource Group with the same Tag

<hr>

## Azure Subscription

- An Azure Subscription provides authenticated and authorized Access to Azure Services
- It also enables the User to provision Resources
- It is a logical Unit of Azure Services associated with an Azure Account
- An Azure Account is an Identity in Azure Active Directory (Azure AD) or in a Directory trusted by Azure AD
- An Account may have one or more Subscriptions, which are Subject to different Billing Models and Access Management Policies
- Azure Subscriptions allow to define following two Limits for Azure Products, Services and Resources:
  - **Billing Limits**: This Subscription Type determines how Azure Usage is billed to an Azure Accounts. This allows the User to create multiple Subscriptions for different Types of Billing Requirements
  - **Access Control Limits**: Azure applies Access Management Policies at the Subscription level. This allows the User to create separate Subscriptions for different organizational Structures

<hr>

## Azure Management Group

- Azure Management Groups are one Domain Level above Subscriptions
- Users organize Subscriptions into Containers called Management Groups and apply their Governance Conditions to the Management Groups
- All Subscriptions in a Management Group automatically inherit the Terms that apply to the Management Group
- Management Groups allow Users to use Governance widely, regardless of the Type of Subscriptions they have
- All Subscriptions in a Management Group must trust the same Azure AD Client

<hr>

## Azure Compute

- Azure Compute is an on-demand Computing Service for running cloud-based Applications
- It provides IT Resources such as Disks, Processors, Memory, Network and Operating Systems
- These provided Resources are available at any Time and are provisioned in a very short Time
- Users pay only for the Resources they use, and only for as long as they use them
- Azure supports a wide Range of Computing Solutions for Developing and Testing, Running Applications, and Expanding Data Centre
- Azure also offers many Services that can run Virtual Machines

### Azure Virtual Machine

- Virtual Machines (VMs) are Software Emulations of physical Computers that have a virtual Processor, Memory, Storage and Network Resources
- VMs host an Operating System and allow Software to be installed and run as on a physical Computer
- Using a Remote Desktop Client, Users can use and control the Virtual Machine like a physical Computer
- With `Azure Virtual Machines`, Users can create and use VMs in the Cloud
- VMs provide Infrastructure-as-a-Service (IaaS), giving the User complete Control over their Operating System and Environment
- VMs allow Users to run their own Software or Custom Hosting Configurations
- Virtual machines are the ideal Choice when the User requires:
  - Full Control over the Operating System
  - The Ability to run their own Software
  - The ability to use Custom Hosting Configurations

#### VM Scaling Groups

- `VM Scaling Groups` are an Azure Computing Resource that allows Users to provision and manage a Group of identical VMs
- Because all VMs in a VM Scaling Group are configured identically, VM Scaling Groups enable true Auto-Scaling, eliminating the Need to provision VMs in Advance
- Auto-Scaling facilitates the Creation of large-scale Services designed for high Computing Power, Big Data and Workloads in Containers
- As Demand increases, more VM Instances can be added; as Demand decreases, VM Instances can be removed
- Scaling can be done manual, automated or a Combination of both

#### Containers and Kubernetes

- `Azure Container Instances` and `Azure Kubernetes Service` are Azure IT Resources that Users can use to deploy and manage Containers
- Containers are lightweight, virtualized Application Environments
- Containers are designed so that Users can create them quickly, scale them horizontally and terminate them dynamically
- Users can run multiple Instances of a containerized Application on a single Host Computer
- `Azure Container Instances` provides the fastest and easiest Way to run a Container in Azure without having to manage VMs or deploy additional Services
- `Azure Kubernetes Service` is an Orchestration Service tasked with Automating, Managing and Interacting with Containers

#### Azure App Service

- `Azure App Services` enables Users to build, deploy and scale enterprise-class Web, Mobile and API Applications that can run on any Platform
- The Applications created can meet rigorous Performance, Scalability, Security and Compliance Requirements using a fully managed Infrastructure Maintenance Platform
- `Azure App Services` is a PaaS (Platform as a Service) Offering

#### Azure Functions

- `Azure Functions` is used when Users only need to worry about the Code that runs their Service, not the underlying Platform (like Operating System and Server) or Infrastructure
- `Azure Functions` is often used when Users need to perform a Task in Response to an Event (often via a REST Request), Timer or Message from another Azure Service, and that Task can be executed quickly (within seconds or less)
- `Azure Functions` are triggered by Events (often via a REST Request), Timers or Messages from other Azure Services to perform their Task
- An `Azure Function App` requires an `Azure Storage Account` that supports Blob, Queue, File, and Table Storage because `Azure Functions` rely on Storage for Operations such as Managing Triggers and Logging Function Executions
- The `Azure Storage Account` used by an `Azure Function App` can also be used by Triggers and Bindings to store Application Data
- A `Azure Function App` provides an Execution Context in which `Azure Functions` are executed, so they are managed, deployed, and scaled together
- All `Azure Functions` in a `Azure Function App` share the same Pricing Plan, Deployment Method, and Runtime Version
- It is also the Unit of Deployment, Management and Scale for `Azure Functions`, so when a `Azure Function App` scales out, more (Cloud) Resources are allocated to run multiple Instances of the `Azure Functions` Host
- `Azure Functions` manage the Infrastructure and the Provisioning/Deprovisioning of Resources according to Demand
- Scaling and Performance Adjustment are also done automatically by `Azure Functions`
- The User is only charged for the Resources actually used
- `Azure Functions` can be either stateless or stateful:
  - If `Azure Functions` are stateless (default), they behave as if they have been restarted each Time they respond to an Event
  - If `Azure Functions` are stateful (called `Durable Functions`), a Context is passed through the Function to track previous Activity
- The Context in which an `Azure Function` runs is called a `Function App`
- A `Function App` is a Unit for Deploying, Managing and Scaling the `Azure Function`
- All `Azure Functions` in a `Function App` share the same Settings and Connections
- All `Azure Functions` within a `Function App` use the same Resource within an Instance and are scaled simultaneously
- The Use of `Application Insights` is integrated with `Azure Functions`
- When `Application Insights` is integrated, Telemetry Data is sent to the associated `Application Insights` Instance
- The Telemetry Data includes Logs generated by the Functions Host, Traces written by the Function Code and Performance Data

##### Azure Functions vs. Azure Logic Apps

- `Azure Functions` can execute Code in almost any modern Programming Language
- `Azure Logic Apps` are created in a Web-based Designer and can execute Logic triggered by Azure Services without writing Code

##### Important Components of Azure Functions

| Component                      | Description                                                                                                                                                                                                                                                                                                                    |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Function Triggers              | Triggers are Events that cause a Function to be executed. A Trigger defines how a Function is called, and a Function must have exactly one Trigger                                                                                                                                                                             |
| Function Bindings              | Binding to a Function provides a Way to declaratively connect another (Cloud) Resource to the Function; Bindings can be connected as Input Bindings, Output Bindings or both. Data from Bindings are provided to the Function as Parameters                                                                                    |
| Function Runtime               | Functions currently supports multiple Versions of the Runtime Host. Functions also support many different Runtimes such as .NET Core, Node.js, Java, PowerShell and Python                                                                                                                                                     |
| API Management                 | API Management provides Security and Routing for the HTTP-triggered Function Endpoints to make them available as a true REST API                                                                                                                                                                                               |
| Provisioning Slots             | Provisioning Slots allow a Functions App to run different Instances called Slots. Slots are different Environments made available through a publicly available Endpoint. Slots provide a Way to test a new Version of Functions in a secure Environment and then seamlessly change the new Version into the production Version |
| Configuration of Function Apps | Connection Strings, Environment Variables and other Application Settings are defined separately for each Function App. The Values for Function App Settings can be read in the Code as Environment Variables                                                                                                                   |

##### Message Queue

- A Message Queue is a Software Component used to handle Messaging between Processes, Threads or Applications
- It can store a Message, and Workers can retrieve the Message when it is appropriate
- Message Queues can generate Events with a Payload, and Azure Functions can listen to such a Message and execute its Code when the Message is published

##### Durable Functions

- `Durable Functions` is an Extension of `Azure Functions` that allows to perform persistent, stateful Operations in in a Serverless Environment
- Azure provides the Infrastructure for Maintaining State Information that can retain the State between Function Calls
- `Durable Functions` are used to orchestrate a long-running Workflow
- `Durable Functions` give all the Benefits of a Serverless Hosting Model, while handling Activities like Monitoring, Synchronization, and Runtime Issues
- Some of the Benefits of using `Durable Functions` are:
  - `Durable Functions` allow to write Event-Driven Code. A `Durable Function` can wait asynchronously for one or more external Events, and then perform a Series of Tasks in response to those Events
  - `Durable Functions` can chain Functions together. This can be used to implement common Patterns such as Fan-Out/Fan-In, which uses one Function to call others in parallel and then accumulate the Results
  - `Durable Functions` can be orchestrated and coordinated, and the Order in which they are executed can be specified
  - The State for `Durable Functions` is managed by Azure, so Developers do not need to write custom Code to store State Information for a `Durable Function`
  - `Durable Functions` can be called both synchronously and asynchronously. Output from the called Functions is saved locally in Variables and used in subsequent Function Calls
  - Azure automatically checkpoints the Progress of a `Durable Function` when the Function is waiting. Azure may choose to dehydrate the `Durable Function` and save its State while the Function waits to conserve Resources and reduce Costs. When the `Durable Function` starts running again, Azure will rehydrate it and restore its State

###### Durable Function Types

- **Client Functions** are the Entry Point for creating an Instance of a `Durable Functions` Orchestration. They can be run in Response to an Event from many Sources, such as a new HTTP Request arriving, a Message being posted to a Message Queue, an Event arriving in an Event Stream
- **Orchestrator Functions** describe how Actions are performed and the Order in which they are performed
- **Activity Functions** are the Basic Units of Work in a `Durable Function` Orchestration. An `Activity Function` contains the actual Work performed by the Tasks being orchestrated

###### Durable Function Patterns

- **Function Chaining**: In this Pattern, the Workflow executes a Sequence of Functions in a specified Order. The Output of one Function is applied to the Input of the next Function in the Sequence. The Output of the last Function is used to produce a Result

<p align="center">
  <img src="https://github.com/michael-steinert/AzureEssentials/assets/29623199/69a5c21b-e3ef-400e-9772-8a3fe6f833b5" alt="Function Chaining" width="30%"/>
</P>

- **Fan Out/Fan In**: This Pattern executes multiple Functions in parallel and waits for all Functions to complete. The Results of the parallel Executions can be aggregated or used to calculate a final Result

<p align="center">
  <img src="https://github.com/michael-steinert/AzureEssentials/assets/29623199/1d70afd7-5f36-4bf8-841f-996e421cad91" alt="Fan Out/Fan In" width="20%"/>
</P>

- **Async HTTP APIs**: This Pattern addresses the Problem of Coordinating the State of long-running Operations with external Clients. An HTTP Call can trigger the long-running Action. It can then redirect the Client to a Status Endpoint. The Client can find out when the Operation has finished by polling this Endpoint

<p align="center">
  <img src="https://github.com/michael-steinert/AzureEssentials/assets/29623199/919ff123-06c1-4e7b-8d97-2c180d0c3a1c" alt="Async HTTP APIs" width="15%"/>
</P>

- **Monitor**: This Pattern implements a recurring Process in a Workflow, possibly Checking for a Change in State. For Example, this Pattern can be used to poll until certain Conditions are met

<p align="center">
  <img src="https://github.com/michael-steinert/AzureEssentials/assets/29623199/a1e02605-a01e-4f88-a560-a7ffa1191ba7" alt="Monitor" width="10%"/>
</P>

- **Human Interaction**: This Pattern combines automated Processes with some Human Interaction. A manual Process within an automated Process is tricky because Humans are not as highly available and responsive as most Computers. Human Interaction can be incorporated using Timeouts and Remediation Logic that kicks in if the Human does not interact correctly within a specified Response Time. An Approval Process is an Example of a Process that requires Human Interaction

<p align="center">
  <img src="https://github.com/michael-steinert/AzureEssentials/assets/29623199/c1b23f17-a1d3-4951-a85a-f41bf6c5e7eb" alt="Human Interaction" width="30%"/>
</P>

###### Webhooks

- Webhooks are User-defined HTTP Callbacks
- They provide a lightweight Mechanism for Applications to be notified by another Service when something of Interest happens through an HTTP Endpoint
- Developers can use a Webhook to trigger an `Azure Function`, and then analyze the Message to determine what happened and how to respond

<hr>

## Azure API Management

- `Azure API Management` transforms, secures and deploys APIs
- `Azure API Management` allows multiple `Azure Functions` to be combined into one integrated API
- `Azure API Management` handles all Tasks related to the Mediation of API Calls, including Request Authentication and Authorization, Rate Limit and Contingency Enforcement, Request and Response Transformation, Logging and Tracking, and API Version Management
- `Azure API Management` supports importing `Azure Function Apps` as new APIs and appending these Apps to existing APIs
- This Process automatically generates a Host Key in the `Azure Function App`, which is then assigned to a named Value in `Azure API Management`
- `Azure API Management` consists of the following Components:
- The **Azure API Gateway** acts as a Reverse Proxy, routing Requests from Clients to Services. It is the Endpoint that:

  - Accepts API calls and routes them to the Backend
  - Verifies API Keys, JWT Tokens, Certificates and other Credentials
  - Enforces Usage Quotas and Rate Limits
  - Transforms the underlying API without Code Changes
  - Caches Backend Responses if the Capability is set up
  - Logs Call Metadata for Analysis

- The **Azure Portal** is the administrative Interface where the Administrator sets up the API Program. It can also be used to:

  - Define or import API Schema
  - Package APIs into Products
  - Set up Usage Policies such as Quotas or Transformations on the APIs
  - Get Insights from Analytics
  - Manage Users

- The **Azure Developer Portal** is the main Web Presence for Developers. From Developer Portal they can:

  - Read API Documentation
  - Try out an API via the Interactive Console
  - Create an Account and subscribe to get API Keys
  - Access Analytics on their own Usage

### API Definition

- To use `Azure API Management`, Administrators define APIs in the DEveloper Portal
- Each API consists of one or more Operations (i.e. Endpoints) and can be added to one or more Products
- To use an API, Developers subscribe to a Product that contains that API and then call the API's Operations (i.e. Endpoints), following any Usage Policies that may apply
- Usage Policies allow the Publisher to change the Behavior of the API through Configuration
- They are a Collection of Statements that are executed sequentially on the Request or Response of an API

### Policies

- Policies are Configurations that allow Administrators to change the Behavior of APIs without changing the underlying Code
- They are implemented as XML Structures consisting of individual Statements that are executed in Sequence
- Policies can be used to set Limits, transform Response Formats, enforce Security Measures, and perform various other Customizations
- In `Azure API Management`, Policies execute at the following Times:
  - **Inbound**: These Policies execute when a Request is received from a Client
  - **Backend**: These Policies execute before a Request is forwarded to a managed API
  - **Outbound**: These Policies execute before a Response is sent to a Client
  - **On-Error**: These Policies execute when an Exception is raised
- The Policy Scope determines how broadly the Policy applies
- The following Policy Scopes are available for the Administrator to choose from:
  - **Global**: Policies applied at the Global Scope affect all APIs within the Instance of `Azure API Management`
  - **Product**: In `Azure API Management` it is possible to group one or more APIs into a single Product and then manage Access to that product as a single Entity. Policies applied to the Product Scope affect all APIs in that Product, but APIs in other Products are not affected
  - **API**: Policies applied at the API Scope affect only a single API
  - **Operation**: Policies applied at the Operation Scope affect only one Operation within the API
- Policies can speed up Responses by Configuring a Cache of prepared Responses; when a Request is received from a User, `Azure API Management` checks to see if there is a suitable Response already in the Cache

### Subscriptions and API Keys

- Subscriptions allow Control of Access to APIs through Segmentation of User Access to an API
- API Keys provide the Authorization to access these Subscriptions
- Whenever a Client makes a request to a protected API, a valid API Key must be included in the HTTP Request or the Request will be rejected
- API Keys can be passed in the Request Header (Ocp-Apim-Subscription-Key) or as a Query String Parameter (subscription-key) in the URL
- The API Key is directly associated with a Subscription, which can be scoped to different Areas, allowing Subscriptions to provide Control over Permissions and Usage Policies
- The three Subscription Scopes are:
- **All APIs**: applies to every API accessible from the `Azure API Gateway`
- **Single API** applies to a single imported API and all of its Endpoints
- **Product**: a Product is a Collection of one or more APIs that is configured through the `Azure API Management`. Products can have different Access Rules, Usage Quotas, and Usage Policies

<hr>

## Azure Cosmos DB

- `Azure Cosmos DB` is a fully managed NoSQL Database designed to provide low Latency, elastic Scalability of Throughput, well-defined Semantics for Data Consistency, and high Availability
- Databases can be configured to be globally distributed and available in any of the `Azure Regions`, enabling lower Latency by Placing Data close to where Users are located

### Azure Cosmos DB Account

- The `Azure Cosmos DB` Account is the basic Unit of global Distribution and high Availability
- It contains a unique DNS Name, and can be managed using the Azure Portal, the Azure CLI, or various language-specific SDKs
- For global Distribution of Data and Throughput across multiple `Azure Regions`, it is required to add or remove `Azure Regions` to the `Azure Cosmos DB` Account
- `Azure Cosmos DB` provides several Database APIs that enable Developers to model real-world Data using Document, Key-Value, Graph, and Column Family Data Models
- These APIs allow Applications to treat `Azure Cosmos DB` as if it were several other Database Technologies, without the Overhead of Management and Scaling Approaches

### Azure Cosmos DB Container

- A Database is analogous to a namespace, and is the Unit of management for a Set of `Azure Cosmos DB` Containers
- An `Azure Cosmos DB` Container is the fundamental Unit of Scalability
- A Container can have virtually unlimited provisioned Throughput, i.e. Request Units per Second (RU/s) and Storage
- A Request Unit (RU) represents the System Resources, such as CPU, IOPS, and Memory, required to perform the Database Operations supported by `Azure Cosmos DB`
- `Azure Cosmos DB` transparently partitions the Container using the logical Partition Key specified by the Administrator to elastically scale the Throughput and Storage provided
- A Container is a Schema-agnostic Container of Items, which allows Items in a Container to have arbitrary Schemas
- By default, all Items added to a Container are automatically indexed without the Need for explicit Index or Schema Management
- Depending on the API used, an `Azure Cosmos DB` Item can represent either a Document in a Collection (MongoDB), a Row in a Table (PostgreSQL), or a Node or Edge in a Graph (Apache Gremlin)

<p align="center">
  <img src="https://github.com/michael-steinert/AzureEssentials/assets/29623199/60735606-72d6-464d-9b06-0913cf03aac9" alt="DB Account Entities" width="75%"/>
</P>

### Data Consistency Levels

- `Azure Cosmos DB` approaches Data Consistency as a Spectrum of Choices rather than two Extremes, i.e. Strong Consistency and Eventual Consistency
- Strong Consistency and Eventual Consistency are at the Ends of the Spectrum, but there are many Data Consistency Options along the Spectrum
- Developers can use these Options to make precise Choices and granular Trade-Offs for high Availability and Performance

<p align="center">
  <img src="https://github.com/michael-steinert/AzureEssentials/assets/29623199/8d8ee6a3-cb8f-4e3e-898b-b1d9db84724f" alt="Data Consistency Levels" width="75%"/>
</P>

#### Strong Consistency

- Strong Consistency provides a Guarantee of Linearizability
- Linearizability describes the Consistency of Operations in a distributed System, i.e. it refers to the concurrent Servicing of Requests
- Reads are guaranteed to return the latest committed Version of an Element
- A Client never sees an uncommitted or partial Write
- Users are always guaranteed to read the latest committed Write

#### Bounded Staleness Consistency

- In Bounded Staleness Consistency, Reads are guaranteed to honour the Consistent Prefix Guarantee
- Reads can lag behind Writes by at most "K" Versions (i.e. Updates) of an Item, or by "T" Time Interval, whichever comes first

#### Session Consistency

- With Session Consistency, Reads within a single Client Session are guaranteed to honour the Consistent Prefix, monotonic Reads, monotonic Writes and Write-Follows-Reads Guarantees
- This assumes a single Writer Session or Sharing of the Session Token for multiple Writers

#### Consistent Prefix Consistency

- With Consistent Prefix Consistency, Updates made as single-document Writes see eventual Consistency
- Updates made as a Batch within a Transaction are returned consistent to the Transaction in which they were committed
- Write Operations within a Transaction of multiple Documents are always visible together

#### Eventual Consistency

- In Eventual Consistency, there is no Order guarantee for Reads
- In the Absence of further Writes, the Replicas will eventually converge
- Eventual Consistency is the weakest Form of Data Consistency, because a Client can read the Values that are older than the ones it read before
- Eventual Consistency is ideal when the Application does not require Order Guarantees

<hr>

## Azure Blob Storage

- In the a `Azure Storage Account`, Developers can store Blobs in Containers called `Azure Blob Storage`
- A Container is a convenient Way to group related Blobs that allow Developers to control who can read and write Blobs within it at the Container Level
- Within a Container, Developers can organize Blobs in a Hierarchy of virtual Folders, similar to Files in a File System on Disk
- `Azure Blob Storage` supports the following Types of Blobs:
  - **Block Blobs**: A Block Blob is treated as a Set of Blocks. Each Block can vary in Size, up to 100MB. A Block Blob can contain up to 50,000 Blocks, for a maximum Size of over 4.7TB. The Block is the smallest Amount of Data that can be read or written as a single Unit. Block Blobs are best used to store discrete, large, binary Objects that change infrequently
  - **Page Blobs**: A Page Blob is organized as a Collection of 512-Byte Pages of fixed Size. A Page Blob is optimized to support random Read and Write Operations. Developers can fetch and store Data for a single Page if required. A Page Blob can hold up to 8TB of Data. Azure uses Page Blobs to implement virtual Disk Storage for Virtual Machines
  - **Append Blobs**: An Append Blob is a Block Blob optimized to support Append Operations. Developer can only add Blocks to the End of an Append Blob; updating or deleting existing Blocks is not supported. Each Block can vary in size, up to 4MB. The maximum Size of an Append Blob is just over 195 GB
- `Azure Blob Storage` provides the following Access Tiers to balance Access Latency and Storage Cost:
  - **Hot Tier** is the default. Developers use this Tier for Blobs that are accessed frequently. Blob Data is stored on high performance Media
  - The **Cool Tier** has lower Performance and a lower Storage Cost than the Hot Tier. It is used for Data that is accessed infrequently. Cool Tier is common for newly created Blobs to be accessed frequently initially, but less frequently over Time. Developers can migrate a Blob from the Cool Tier back to the Hot Tier
  - The **Archive Tier** provides the lowest Storage Cost, but with increased Latency. It is for historical Data that can not be lost but is rarely needed. Blobs in the Archive Tier are effectively stored in an offline State. Typical Read Latency for the Hot and Cool Tiers is a few Milliseconds, but for the Archive Tier it can take Hours for the Data to become available. To retrieve a Blob from the Archive Tier, Developers must change the Access Tier to Hot or Cool Tier, then the Blob is rehydrated

<hr>

## Azure Tables Storage

- `Azure Table Storage` is a NoSQL Storage Solution that makes Use of Tables containing Key-Value Data Items
- Each Item is represented by a Row that contains Columns for the Data Fields that need to be stored
- `Azure Table Storage` allows Developers to store semi-structured Data
- All Rows in a Table must have a unique Key (composed of a Partition Key and a Row Key), and when Developers modify Data in a Table, a Timestamp Column records the Date and Time the Modification was made; otherwise, the Columns in each Row can vary
- Tables in `Azure Table Storage` have no Concept of Foreign Keys, Relationships, stored Procedures, Views, or other Objects that Developers might find in a relational Database
- Data in `Azure Table Storage` is typically demoralized, with each Row containing the entire Data for a logical Entity
- To ensure fast Access, `Azure Table Storage` divides a Table into Partitions
- Partitioning is a Mechanism for Grouping related Rows based on a common Property, or Partition Key, so that Rows with the same Partition Key are stored together
- Partitioning can improve Scalability and Performance as well as Helping to organize Data in the following Ways:
  - Partitions are independent of each other and can grow or shrink as Rows are added to or removed from a Partition. A Table can have any number of Partitions
  - When Searching for Data, Developers can include the Partition Key in the Search Criteria. This helps to narrow down the Amount of Data to examine and improves Performance by Reducing the Amount of I/O (Input and Output Operations, or Reads and Writes) required to find the Data
- The unique Key in an `Azure Table Storage` consists of two Elements: the Partition Key, which identifies the Partition containing the Row, and a Row Key, which is unique to each Row in the same Partition

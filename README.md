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
  <img src="https://github.com/michael-steinert/KubernetesEssentials/assets/29623199/82b20636-68ed-4937-84a1-9f2c0ad9d6c1" alt="Shared Responsibility" width="50%"/>
</P>

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

#### Governance

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

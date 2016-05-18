# Service Design
## Design Coordination:
Ensures the goals and objectives of the Service Design phase are met by providing and maintaining a single point of coordination and control for all activities; (ensures all service models conform to strategic, architectural, governance, and other corporate requirements)
* Ensures that Utility and Warranty requirements are properly addressed
* Consistent approach to design activities; Consistent approach across projects, changes, suppliers, support team
* Manage/coordinate resources
* Input to SDP; ensure smooth handover to Service Transition
* Monitor/improve Service Design phase

### Scope:
all activities within the Service Design phase

## Service Catalog Management (SCatM):
provides a single source of consistent information for all live and transitioning services.
* Ensures that a Service Catalog is produced and maintained and that it is accurate and current and widely available to those that are approved to access it

Service Catalog describes the services in use and those able to be deployed, the business processes they enable and the levels and quality of service customers can expect.

### SCatM Key concepts:
* A subset of the Service Portfolio
* The SCat Manager is responsible for creating a Service Catalog, and BRM or SLM processes also contribute
* Published to customers and users
* Structures:
  * 2-view
    * Business/Customer Service Catalog:
      * Contains details of all IT services delivered to customers
      * Relates the IT services to business units and business processes
      * The customer view of the Service Catalog
    * Technical/Support Service Catalog
      * Contains details of all the supporting IT services
      * Relates the IT services to supporting and shared services, components and CIs
      * Underpins the Business Service Catalog does not form part of customer view
  * 3-view
    * Wholesale Customer view
      * All IT Services delivered to wholesale customers
      * Relationship with customers
    * Retail Customer view
      * All IT services delivered to retail customers
      * Relationship with customers
    * Support Services view
      * Details of support IT services
      * Relates the IT services to supporting and shared services, components, and CIs

## Service Level Management (SLM):
Ensures an agreed level of services is provided for all current and future services
* Defines, negotiate, document, agreed, monitors, measures, reports, and reviews the service levels
* Good cooperation between BRM and SLM for good customer relationship
* Ensures measurable targets
* Improve customer satisfaction
* Manage expectations

### Scope:
lifecycle of the service.

### SLM Key Concepts:
* Out of scope activities:
  * Negotiation/agreement of service functionality (utility); we talk about service side such as: security, availability, capacity
  * Contract negotiation (Supplier Management is a different process)
* BRM-SLM Relationship
* Service Level Requirement (SLR): Customer Requirement for an aspect of an IT Service.
* Service Level Agreement (SLA): agreement between an IT Service Provider and a Customer
* Operational Level Agreement (OLA): internal perspective between 2 parts of the same organization; includes objectives that underpin the service targets agreed in an SLA
* Service Level Target (SLT): commitment that is documented in an SLA. SLTs are based on SLRs and are needed to ensure that the IT Service design is fit for Purpose. SLTs should be SMART
* Underpinning Contract (UC): a contract between an Service Level Manager and a supplier
* Service Improvement Plan (SIP): a formal Plan to implement improvements to a Process or IT Service
* SLA Monitoring (SLAM) is used to help monitor and report achievements against SLT
* SLAM Chart (RAG Chart): to show whether each agreed SLT has been met, missed, or nearly missed

<img src="https://user-images.githubusercontent.com/31813625/32967972-89ecce62-cbad-11e7-900b-7a6096cb5d6e.png" width="314" height="115" />

### SLM Activities:
* Design SLA frameworks (types of SLA)
  * Service-based: This is where an SLA covers one service, for all the customers of that service (Premium, Gold, Silver, etc…)
  * Customer-based: This is an agreement with an individual customer group, covering all the services they use.
  * Multi-level: (corporate level, customer level, and service level)
  * The wording of SLAs should be clear and concise and leave no room for ambiguity. There is normally NO need for agreements to be written in legal terminology. It is recommended that all SLAs contain a glossary, defining any terms and providing clarity for any areas of ambiguity. it is essential that the targets documented and agreed are clear, specific and unambiguous; Ensure the agreement is signed as both sides have responsibilities
* Agree on SLRs, SLAs, and <u>underpinning agreements</u> (OLAs & UCs)
* Monitor, measure, and report on service performance
* Review services and agreements
* Measure and improve customer satisfaction
* Logs and manages complaints and complements
* Manage customer expectations
* Develops contacts and relationships

## Availability Management:
I want to call availability as up-time of services and up-time of components. Availability Management ensures the level of service availability delivered matches or exceeds the current and future agreed needs of the business in a cost-effective manner.
* Ensuring services are able to meet availability targets
* Monitoring and reporting actual availability
* Improvement activities, to ensure that services continue to meet or exceed their availability goals
* Produces and maintains an Availability Plan
* Provides advice to the business and IT on all availability-related issues
* Ensures service availability meets or exceeds the agreed targets
* Assists with the resolution of incidents and problems
* Assesses the impact of changes
* Ensures implementation of proactive measures to improve availability
* Proactive and Reactive Availability Management

### AM-Key Concepts:
* Availability Management Information System (AMIS), (AMIS is also part of SKMS)
* IT Service Availability: involves all aspects of service availability and unavailability and the impact of component availability, or the potential impact of component unavailability on service availability
* Component Availability: involves all aspects of component availability and unavailability
* Vital Business Functions (VBFs): A Function of a Business Process that is critical to the success of the Business. Vital Business Functions are an important consideration of Business Continuity Management, IT Service Continuity Management and Availability Management
  * High Availability: minimizes the effects of IT component failure
  * Fault Tolerance: availability to operate correctly after failure
  * Continuous Operations: an approach or design to eliminate planned downtime of an IT service. Note that CIs may be down even though the IT service remains available
  * Continuous Availability: an approach or design to achieve 100% availability
* ARRMSS:
  * Availability: Percentage of a CI or IT Service to perform its agreed Function when required
  * Reliability: How long a CI or IT Service can perform its agreed Function without interruption
  * Resilience: The ability of a CI or IT Service to resist Failure or to recover quickly
  * Maintainability: How quickly a CI or IT Service can be restored to normal working
  * Serviceability: The ability of a Third-Party Supplier to meet the terms of its Contract
  *Security

## Capacity Management:
The Process responsible for ensuring that the Capacity of IT Services and the IT infrastructure is able to deliver agreed Service Level Targets in a Cost Effective and timely manner.
### Capacity:
The maximum Throughput that a Configuration Item or IT Service can deliver whilst meeting agreed Service Level Targets (SLT). For some types of CI, Capacity may be the size or volume, for example a disk drive, RAM, CPU, BW, etc.
### Capacity Management:
* Produces and maintains a Capacity Plan
* Provides advice to the business and IT in all capacity and performance-related issues
* Ensures service performance meets or exceeds agreed targets
* Assists with the resolution of capacity-related Incidents and Problems
* Assesses the impact of Changes
* Ensures implementation of proactive (not reactive) measures to improve capacity
* SPOC for all IT performance and capacity-related issues

### Capacity Management – Key Concepts
* 3 sub processes:
  * Business Capacity Management (BCM)
    * Focus: current/future requirements
    * Translates business plans into service and IT infrastructure requirements
    * Ensures sufficient capacity to support future services implemented on appropriate timescale
  * Service Capacity Management (SCM)
    * Focus: delivery of service that support the business
    * Understands the IT services, their use of resource, working patterns, peaks and troughs, etc…
    * Ensures that the services meet the agreed capacity service targets
  * Component Capacity Management (CCM)
    * Focus: underpinning IT infrastructure
    * Understands the performance, capacity, and utilization of each component of the IT infrastructure
    * Ensures the optimum use of components
  * Capacity Management Information Service (CMIS): A virtual repository of all Capacity Management data, usually stored in multiple physical location (think about SKMS, CMIS is also part of SKMS); includes:
    * Business data: Information on the current and future needs of the business
    * Service Data: Service performance data
    * Component utilization data: utilization, threshold, limit information of all technical components
    * Financial data: because Capacity Management’s job is to provide cost-justifiable IT capacity
  * Capacity Plan
    * Key output
    * Published on the budget cycle
    * Investment document
    * Details current need, projected need, and proposed need: Allows for business decisions based on fact
    * Once the Service Strategy and plans are reviewed, the Capacity Plan can be used to anticipate future requirements for IT resources

## IT Service Continuity Management:
Supports overall Business Continuity Management by ensuring the required IT technical and service facilities can be resumed within required and agreed business timescale.
* Ensures business survival by reducing impact of disaster or major failure
* Reduces service vulnerability and risk to the business
* Maintains a pre-determined level of service in the event of a disaster
* Preserves high customer and user confidence
* Unresolved problem that might cause major business disruption should be escalated to ITSCM

### ITSCM - Key Concepts
* Business Impact Analysis (BIA)
  * Identifies Vital Business Functions (VBF) and their dependencies. These dependencies may include suppliers, people, other Business Processes, IT Services, etc.
  * Quantifies impact of service loss
  * Defines VBFs
* Risk Assessment: initial steps of Risk Management
  * Assess the impact of potential threats on service assets
  * Develops countermeasures based on risk
  * Risk: A possible event that could cause harm or loss, or affect the ability to achieve Objectives
  * Risk Assessment can be quantitative (based on numerical data) or qualitative
* Risk Management: The Process responsible for identifying, assessing, and controlling Risks

<img src="https://user-images.githubusercontent.com/31813625/32968476-5d4f5c74-cbaf-11e7-83c1-03729fd9ea40.png" width="381" height="169" />

## Information Security Management:
Aligns IT security with business security and ensures that information security is effectively managed in all service and Service Management Activities.
* Ensures security risks are identified, analyzed and managed
* Ensures that information resources are used responsibly and protected
* Protects the interests of those relying on information, and the systems and communications that deliver the information, from harm
* ISM must be considered in the overall corporate governance framework
* Information Security ensures that services are used in an appropriate way by the appropriate people
* Objectives:
  * Confidentiality: protects the data from unauthorized access
  * Integrity: ensures data is accurate and protected from unauthorized change
  * Availability: ensures the data is available as and when required
  * Appropriateness: services used in an appropriate manner
  * Trustworthiness: transactions and data exchanges can be trusted

### ISM – Key Concepts:
* Information Security Policy must have full support from top management; includes
  * Everybody (All customers, users, and IT staff) has access to Information Security Policy
  * Use/misuse IT assets
  * Access/password controls
  * Policies for email, internet
  * Supplier access
  * Asset disposal
  * …
* Information Security Management System (ISMS) stores information required to manage ISM activities
  * CMDB, CMS, SKMS

## Supplier Management:
Manages suppliers and their services to provide seamless IT service quality and ensure value for money.
* Ensures all contracts with suppliers support the needs of the business and all suppliers meet their contractual commitments
* Manages supplier relationships and performance (ensures value for money)
* Supplier and contract categorization and risk assessment
* Supplier and contract evaluation and selection
* Development, negotiation and agreement of contracts
* Contract review, renewal and termination
* Maintenance of standard contracts, terms and conditions
* Aligns with ITSM process requirements, particularly Security and IT Service Continuity Management
* Implementation and enforcement of the supplier policy
* Agreement and implementation of service and supplier improvement plans
* Maintenance of a Supplier and Contract Database (SCD): A database or structured Document used to manage Supplier Contracts throughout their Lifecycle; link those contracts with our SKMS:
  * CMDB, CMS, SKMS
* Supplier Categorization
  * Strategic: significant partnering relationship; Sr. Managers manage
  * Tactical: significant commercial impact and business interaction; Middle Managers manage
  * Operational: provides operational product/services; managed by Jr. Operational Managers
  * Commodity – low-value, easily sourced
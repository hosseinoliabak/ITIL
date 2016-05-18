# Introduction to Information Technology Infrastructure Library (ITIL) Foundation:
## ITIL:
Describes how IT resources should be organized to deliver business value,
documenting the processes, functions, and roles of IT Service Management.
(ITIL is not a standard; it is a framework; it is non-prescriptive)
(It is best practice for quality IT Service Management)
(ISO/IEC 20000 is aligned with ITIL Best Practice).
ITIL is owned by the OGC and is vendor neutral. There are many external
methods, practices and frameworks that align well to ITIL practices.
* ITIL v1: 1985, 31 books
* ITIL v2: 1999, 9 books
* ITIL v3: 2005 (efforts started), 5 books + several complementary
publications

### Best Practice:
Proven Activities or Processes that have been successfully used by
multiple Organizations.
* Sources (generate): Standards, Industry practices, Academic research,
Training & education, Internal experience
* Enablers (aggregate): Employees, Customers, Suppliers, Advisors,
Technologies
* Drivers (filter): Substitutes, Regulators, Customers
* Scenarios (filter): Competition, Compliance, Commitments

### Good Practice = Guidance from Best Practice +
Proprietary Knowledge + Public Frameworks + Standards +
Academic research + Training.

### The Two Components of ITIL V3:
* The ITIL Core Publications: 5 cores (Service Strategy, Service Design,
Service Transition, Service Operation, Continual Service Improvement)
* The ITIL Complementary Guidance: some of these materials are printed
and some of these are only found online on ITIL online portal called
ITIL Live. (these materials are not part of Foundation Exam).

### ITIL Benefits:
* IT Service improvement
* Cost reduction
* Customer satisfaction
* Improved productivity
* Improved third-party management

### Governance:
Ensuring that policies and strategies are actually implemented and their
required processes are correctly followed.

#### Types of Governance:
* Enterprise governance
* Corporate governance
* IT governance: consists of the leadership, organizational structures,
and processes

### Service:
Service is a means of delivering value to customers by facilitating
outcomes customers want to achieve without the ownership of specific
costs and risks.

#### Service Provider types:
Service Strategy defines three broad types of Service Providers with
whom a customer is likely to engage in accessing services:
* <i>Internal service provider:</i> business functions embedded within
the business units they serve
* <i>Shared service provider:</i> An internal service provider that
provides shared IT services to more than one business unit. The services
of such shared functions are consolidated into an autonomous special
unit called a shared services unit (SSU)
* <i>External service provider:</i> provides IT services to external
customers

#### Service packages (types of services):
* <i>Core services:</i> deliver the basic outcomes desired by the
customer; services that must be there
* <i>Enabling services:</i> are basic factors; must be in place for the
core services to be delivered
* <i>Enhancing services:</i> are excitement factors


#### ITIL Users vs Customers:
##### User:
A user is a person who uses the IT Service on a day-to-day basis.
Users are distinct from Customers, as some Customers do not use the IT
Service directly.
##### Customer:
Someone who buys goods or Services. The Customer of an IT Service
Provider is the person or group that defines and agrees the Service
Level Targets for/with the Service Provider.

#### Service Management:
Service Management is a set of specialized organizational capabilities
(Functions and Processes) for providing value to Customers in the form
of services.

## ITIL Core Components (Components of the Service Lifecycle):
Each phase of the ITIL Service Life Cycle is represented by a volume in
the ITIL Core Library. Together, these volumes provide an integrated
approach to Service Management throughout ITIL Service Life Cycle.

<img src="https://user-images.githubusercontent.com/31813625/32945800-d4e9e350-cb62-11e7-97ba-aceeb79ddb94.PNG" width="721" height="250" />

Eight of these processes are called Lifecycle Processes because their
activities span all five phases of the service lifecycle. These eight
lifecycle processes are: Service Portfolio Management, IT Service
Financial Management, Capacity Management, Availability management,
Supplier Management, Change management, Service Asset & Configuration
management, Knowledge Management.

### How communication and feedback flows between lifecycle phases:
<img src="https://user-images.githubusercontent.com/31813625/32945940-6527386e-cb63-11e7-9b53-5d539fc6df72.png" />

### Process vs Function:
#### Process:
Process is a structured set of activities designed to accomplish a
specific objectives. Processes are closed-loop systems. A process takes
one or more inputs and turns them into defined outputs.

<img src="https://user-images.githubusercontent.com/31813625/32946069-f325f948-cb63-11e7-9b91-5a2d6f48d24c.png" width="592" height="219" />

##### Process Characteristics:
* Are measurable: in terms of (progress, effectiveness, efficiency,
cost-effectiveness)
* Have specific results
* Deliver to customers: every process delivers its primary result to a
customer or stakeholder
* Respond to a specific event

#### Function:
Functions are units of organizations (teams, groups) specialized to
perform certain type of work and are responsible for specific outcomes.
Such as: Service Desk (Central point of contact between us as IT Service
Provider and users), Technical Management, Application Management, and
IT Operations Management.

Think of functions as self-contained units of organizations or teams who
share the same goals.

##### Group:
A number of people who are similar in some manner, activities, may work
on different technologies.

##### Team:
Formal type of group

#### Coordination between functions via shared process:
Process is going to flew through a function. (NOT to define activities
those are executed by a single function)

---Incident--->[ Service Desk ]---Escalate--->[Application Management]<br />
-------------------------------Process-------------------------------><br />
Activities --> Process --> Function<br />

##### Outcome:
The result of carrying out an Activity; following a Process; delivering
an IT Service, etc.

### Roles:
* <b>Process Owner:</b> A Role responsible for ensuring that a Process is Fit for Purpose. The responsibilities include sponsorship, defining the process Strategy, Design, <b><u>D</u></b>ocumenting the process, <b><u>E</u></b>ducating relevant staff, <b><u>M</u></b>easuring and monitoring the process against the KPIs, CSFs, and other metrics, and Continual <b><u>I</u></b>mprovement of the Process (<b><u>DEMI</u></b>). This Role is often assigned to the same person who carries out the Process Manager Role; Process Owner is NOT responsible for developing IT plans that meet the IT requirements of the business
* <b>Process Manager:</b> A Role responsible for Operational management of a Process. (not in exam)
* <b>Service Owner:</b> A Role that is accountable for a specific Service within an organization. Service owners are as important to Service Management as process owners. Does NOT mean to carry out the day-to-day monitoring and operation of the service they own
* Other roles are not in exam

### RACI Model / Authority Matrix:
* <b><u>R</u>esponsible:</b> the person or group responsible for action getting the job done (>=1)
* <b><u>A</u>ccountable:</b> single individual accountable for the quality outcome (the process owner) (=1)
* <b><u>C</u>onsulted:</b> people who provide input into the process activities (>=0)
* <b><u>I</u>nformed:</b> people who are kept up-to-date on the progress and the activities (>=0)

### Stakeholder:
A person who has an interest in an organization, project, IT service etc... Stakeholders may be interested in the activities, targets, resources or deliverables. Stakeholders may include customers, partners, employees, shareholders, owners etc…

### SMART:
acronym, giving criteria to guide in the setting of objectives:
* <u>S</u>pecific: the need for a specific goal rather than a more general one
* <u>M</u>easurable: the need for criteria for measuring progress toward the attainment of the goal
* <u>A</u>chievable: the importance of goals that are realistic and also attainable
* <u>R</u>elevant: the importance of choosing goals that matter
* <u>T</u>imely: specify when the result(s) can be achieved

### Single Point of Contact (SPOC):
Providing a single consistent way to communicate with an Organization or Business Unit. For example, a Single Point of Contact for an IT Service Provider is usually called a Service Desk.

### Acceptance:
Formal agreement that an IT Service, Process, Plan or other Deliverable is complete, accurate, reliable and meets its specified Requirements. Acceptance is usually preceded by Evaluation or Testing and is often required before proceeding to the next stage of a Project or Process.

### Priority:
A Category used to identify the relative importance of an Incident, Problem or Change. Priority is based on Impact and Urgency, and is used to identify required times for actions to be taken. Priority = Impact + Urgency
* <b>Impact:</b> A measure of the effect of an Incident, Problem or Change on Business Processes
* <b>Urgency:</b> A measure of how long it will be until an Incident, Problem or Change has a significant Impact on the Business. For example, a high Impact Incident may have low Urgency, if the Impact will not affect the Business until the end of the financial year

<img src="https://user-images.githubusercontent.com/31813625/32949182-e97f3204-cb6f-11e7-86d0-01a7c2f6eff5.png" width="466" height="312" />

# Service Strategy
Service Strategy is the core and most important phase of a service.
* Strategy: A Strategic Plan designed to achieve defined Objectives
* Strategic: The highest of three levels of Planning and delivery (Strategic, Tactical, Operational)

## Service Strategy Goal:
How to design, develop, and implement Service Management not only as an organizational capability but as "<u>strategic asset</u>".
* What is a strategy?
* Clear service definition
* What customers are looking for?
* What is the value, how we create it and how is delivered it?
* Opportunity, how to exploit those opportunities?
* Organizational capabilities, internally and from customer side
* Documentation and Coordination

## Scope:
1.	Guidance on setting strategy, policies, and objectives
2.	Marketing, long-term planning

## Processes:
* Strategy Management
* Service Portfolio Management *
* IT Service Financial Management *
* Demand Management: understanding customer usage of services and how this varies over time
* Business Relationship Management (BRM) *<br />
     *<i>Important for ITIL foundation course</i>

## Value Creation:
The value of a service to a customer is influenced by the following:
* The attributes of the service: actual, objective characteristics. The company has direct control over these attributes
* The customer’s perceptions: Company has some control over a customer’s perceptions; advertising can be used
* The customer’s pre-established preferences: customers have they own habits, likes, and dislikes; The company cannot do very much to change a customer’s preferences
* Actual business outcomes: The company has control over this
* The customer’s self-image or positioning in the market: How do customers feel when they think of themselves using the service?

![image](https://user-images.githubusercontent.com/31813625/32951121-c80e57f6-cb76-11e7-9a35-3f6235b23c2a.png)

### Value:
Customer perception and business outcomes.

Utility + Warranty = Value
* Utility  What? Purpose: effective,
* Warranty  How? Use: availability, capacity, continuity, security

## Service Assets: Capabilities and resources
Service assets are basis for value creation; fall into two groups: Capabilities and Resources.
Capabilities are intangible; resources are tangible and easier to acquire.
![image](https://user-images.githubusercontent.com/31813625/32951195-0f48f216-cb77-11e7-9786-c4aa79b72969.png)

## Service Strategy – Value to the Business:
* Linking activities of the service provider to business outcomes
* IT provides value and not just a cost
* Clearly defined levels/types of service to meet/enhance customer outcomes
* Quick response, greater flexibility; agile delivery
* Portfolio of service  positive business return
* Service Strategy provides guidance to IT Service Providers and customers to assist in operations and developing a clear service strategy
  * Questions to invoke strategic planning

# Service Design:
We put the output from Service Strategy to Service Design.

## Design:
An Activity or Process that identifies Requirements and then defines a solution that is able to meet these Requirements.

## Service Design Goal:
To assist the development and design of a service and the Service Management process. This volume describes design principles that convert strategic objectives into a workable service or a portfolio of services. This volume can be used to create a new service or improve an existing service

## Service Structure (4 Ps):
A well-defined and well-implemented service depends on the effective use of the 4 Ps of Service Design:
* People: managers, staff, skills, knowledge, roles, responsibilities, attributes…
* Processes: are used to manage IT services internally and externally; actions, activities, changes…
* Products: services, software, technology, and tools
* Partners: suppliers, manufacturers, and vendors

## 5 Aspects of Design (STAPM):
To ensure a holistic nature of service design and the desire to achieve the results and create the value defined in service strategy.
1.	Service <b><u>s</u></b>olutions new/changed services: design new or changed services (functional requirements, resources, capabilities needed and agreed)  output: Service Design Package (SDP)
2.	Management information systems & <b><u>t</u></b>ools: design tools needed to manage, control, support services; Service Portfolio
3.	Technology/management <b><u>a</u></b>rchitecture: design technologies needed to provide services as well as including all areas of the 4Ps of Service Management
4.	<b><u>P</u></b>rocesses required: Define inputs/outputs & activities; establish norms and standards for performance
5.	<b><u>M</u></b>easurement methods & metrics: defines metrics that access service quality (e.g., process, fulfillment, effectiveness, efficiency)

## Processes:
* Design Coordination *
* Service Catalog Management *
* Service Level Management *: Policies, plans, reports, SIP, SLRs, SLAs, OLAs
* Capacity Management *: Policies, plans, reports, CMIS, sizing, forecasts
* Availability Management *: Policies, plans, reports, AMIS, design criteria, risk analysis, schedules
* IT Service Continuity Management *: Policies, plans, reports, BIA, BCPs, ITSCPs, risk analysis, schedules
* Information Security Management *: Policies, plans, reports, risk analysis, classification, controls
* Supplier Management *: Policies, plans, reports, SCD, contracts

## Key Concepts:
* RACI Model / Authority Matrix: Responsible, Accountable, Consulted, Informed
* Sourcing Strategies
* Service Design Package (SDP)
* 4 Ps of Service Design: People, Processes, Products, Partners

## SDP:
Defines all aspects of IT services throughout their life cycle. The SDP is critical for, and provided to, Service Transition, Service Operations, and Continual Service Improvement.  You create an SDP for each new IT Service, major Change, or IT Service Retirement. This SDP is a document required for the next phase, Service Transition

### Elements of SDP:
For the exam, keep it easy. SDP contains everything including kitchen sink. If you are given a list of items that might be included, look for an “All of the above” option for your answer
* Requirements:
  * Agreed and documented business requirements
  * Service applicability
  * Service Contacts
* Service Design details
* Organizational Readiness Assessment
* Service Lifecycle plan
  * Service Program
  * Service Transition Plan: A plan for transition of the service
  * Service Operational Acceptance Plan
  * Service Acceptance Criteria (SAC): A set of criteria used to ensure that an IT Service meets its functionality and Quality Requirements and that the IT Service Provider is ready to operate the new IT Service when it has been deployed

## Automation Consideration:
Automation is considered to improve the utility and warranty of services. The following are some of the areas where Service Management can benefit from automation:
* Design and modelling
* Service catalogue: automated Service Catalogue
* Pattern recognition and analysis: to handle routine service requests (Problem, and Event Management)
* Classification, prioritization and routing: to handle routine service requests (Incident, Problem, and Change Management)
* Detection and monitoring (Event Management, Incident Management)
* Optimization

## Service Design – Value to Business:
* Reduced Total Cost of Ownership (TCO)
* Improved Quality of Service (QoS)
* Improved Consistency of Service (CoS)
* Improved IT Governance (ITG)
* Improvement service alignment (with customer requirements)
* More effective service performance
* Easier implementation of new/changed services
* More effective service management and IT processes
* Improved information and decision-making

# Service Transition (ST):
We put the output from Service Strategy and Service Design into Service Transition.

## Transition:
Movement, passage, or change from one position, state, stage, subject, concept, etc., to another; change: the transition from adolescence to adulthood.

## Service Transition Goal:
To create a framework that ensures a smooth transition between Service Design and Service Operation. This volume includes guidelines for assessing and controlling risks and managing changes to reduce the chance of unexpected results, failures, or setbacks. Effective Service Transition can significantly improve a service provider’s ability to handle high volume of Changes and Releases.

### Tip:
Service Transition is the lifecycle phase where techies get to do their testing and tinkering. “Transition”, “Test”, “Tinker” all starts with the letter T. This is where the action happens

## Processes:
* Transition Planning & Support (TPS) *
* Change Management *
* Service Asset & Configuration Management (SACM) *
* Release & Deployment Management (RADM) *
* Service Validation & Testing (SVT)
* Change evaluation
* Knowledge Management

## Key Concepts:
Service Knowledge Management System (SKMS): A set of tools and databases that are used to manage knowledge and information. Consists of 4 layers:
* <b>Presentation Layer:</b> Portals, Scorecards, Dashboards, IT governance view, Quality Management view, Service View, Asset/Config View, Service Desk/Support View, Self-Service View
Search, Browse, Store, Retrieve, Update, Publish, Subscribe, Collaborate
* <b>Knowledge Processing Layer:</b> Query and Analysis, Reporting, Performance Management, Modeling, Monitoring & Alerting
* <b>Information Integration Layer:</b> Service Knowledge Management Base: Integrated CMDB + Other integrated data & information.
Schema mapping, metadata management, reconciliation,
(AMIS, CMIS, KEDB, SCD, Partner Info, Business Influences)
* <b>Data Layer:</b> CMDB (Configuration Management Database), Service Portfolio, Other structured data, Unstructured data, and External database link. Event Management
Discovery, Collection, and Audit

### CMS:
Central view point of one or more CMDBs <br />
MDBs  CMS  feed for SKMS

<img src="https://user-images.githubusercontent.com/31813625/32951812-47bb42c8-cb79-11e7-97ab-0b2a071a3f24.png" width="484" height="252" />

### Configuration Item (CI):
Any Component that needs to be managed in order to deliver an IT Service (IT Services, hardware, software, buildings, people, and formal documentation such as Process documentation and SLAs). Information about each CI is recorded in a Configuration Record within the Configuration Management System and is maintained throughout its Lifecycle by Configuration Management. CIs are under the control of Change Management.

## Service V-Model:
The Service V Model is a unique concept that provides a path to follow with regard to defining the requirements for a service package, designing the package, building and then testing the package.
The left-hand side represents the specification of the service requirements down to the detailed Service Design. The right-hand side focuses on the validation and testing activities that are performed against the specifications defined on the left-hand side. Example:

![image](https://user-images.githubusercontent.com/31813625/32951987-c811e0bc-cb79-11e7-9768-11db053821eb.png)

## Service Transition – Value to Business:
* Adapt quickly to new requirements and market developments
* Manage mergers, de-mergers, acquisitions, and transfer of services
* Improve success rate of change and release activities
* Improve predictions of service levels and warranties for new/changed services
* Compliant with business and governance requirements during a change
* Less variation between estimated and actual budgets/plans
* Increase productivity of [not only IT department but also] business/customer
* Maintenance contracts stopped when components are decommissioned or disposed
* Understand risk during and after change

# Service Operation (SO):
 This is the only phase that truly is visible for the customers.

## Operation:
 Day-to-day management of an IT Service, System, or other Configuration Item. Operation is also used to mean any pre-defined Activity or Transaction. For example: loading a magnetic tape, accepting money at a point of sale, or reading data from a disk drive.

## Service Operation goal:
To coordinate and carry out the activities and processes required to deliver and manage services at agreed levels to business users and customers

## Scope:
* The services
* Service Management processes
* Technology
* People

## Processes:
* Event Management *
* Incident Management *: help to minimize outages on a day-to-day basis
* Problem Management *: help to minimize outages on a day-to-day basis
* Request Management *
* Access Management *

## Functions:
Functions are self-contained units. May be broken up and performed by several department, team and groups or may be embodied with a single unit.
* Service Desk: answering calls from users
* Technical Management: supporting the infrastructure
* IT Operations Management: executing day-to-day “behind-the-scenes” activities
* Application Management: maintaining the software

## Communication in Service Operation:
Must have an intended purpose or a resultant action; clear audience.
* Routine operational Communication: regular and is communicated in daily, weekly and monthly cycles
* Communication between Shifts: At the handover of every shift
* Performance Reporting:
  * IT Service Performance: As defined in the SLAs and OLAs
  * Service Operation team or department
  * infrastructure or process
* Communication in Projects
* Communication related to Change
* Communication related to exceptions
* Communication related to emergencies
* Communication with user and customers: Communication with users and customers is ongoing
* Training on new or customized processes and service designs

## Standard Operating Procedures (SOP):
The SOPs are a set of documents containing detailed instructions and activity schedules for every IT Operations Management team, department, or group

## Achieving balance in Service Operation:
Some of the key tensions and conflicts and identifies how IT organizations can recognize that they are suffering from an imbalance by tending more towards one extreme or the other:
* External business view: is the way in which services are experienced by its users and customers. They do not always understand, nor do they care about, the details of what technology is used to manage those services. All they are concerned about is that the services are delivered as required and agreed.
  * Extreme external focus: poor consistency of delivery; generalist staff…
* Internal IT view: is the way in which IT components and systems are managed to deliver the services. Since IT systems are complex and diverse, this often means that the technology is managed by several different teams or departments – each of which is focused on achieving good performance and availability of ‘its’ systems.
  * Extreme internal focus: high consistency of delivery; specialized staff, but none of them know what services are offered to the business
* Extreme focus on stability: IT can demonstrate that it is complying with Standard Operating Procedures (SOPs) and OLAs even when there is clear misalignment to business requirements
* Extreme focus on responsiveness:  IT staff are not available to define or execute routine tasks because they are busy on projects for new services
* Extreme focus on quality of service: Escalating budgets; IT services generally deliver more than is necessary for business success
* Extreme focus on cost of service: Quality of service suffers; There is no way of linking activities in IT to the delivery of IT services
* Extremely reactive: Preparing to deliver new services takes a longtime because each project is dealt with as if it is the first; Similar incidents occur again and again; Staff turnover is high and morale is generally low
* Extremely proactive: Money is spent before the requirements are stated; IT staff tend to have been in the organization for a long time and tend to assume that they know the business requirements better than the business does

## Service Operation – Value to Business:
* Reduce unplanned labor costs
* Reduce frequency/duration of outage
* Meaningful management information
* Meet organizational security requirements (Access Management)
* Standardized service improves productivity and quality of service delivery; promotes automation

# Continual Service Improvement (CSI):
Touches all other 4 ITIL phases; CSI provides guidance on how to identify ways to improve process <b><u>p</u></b>rogress, <b><u>e</u></b>ffectiveness, <b><u>e</u></b>fficiency, and <b><u>c</u></b>ost-effectiveness (PEEC). It also provides guidance on improving services and the technology that supports those services. In addition, CSI also helps us understand what to measure and why it is being measured

## Goal:
To ensure that Service Management processes continue to provide value for customers through continual evaluation and improvement of the quality of services

## CSI Key Terms:
* **Metric:** Something that is measured and reported to help manage a Process, IT Service or Activity
* **KPI (Key Performance Indicator):** A metric that is used to help manage a Process, IT Service, or Activity. Many metrics can be measured, but only the most important of these are defined as KPIs and used to actively manage and report on the Process, IT Service or Activity. KPIs should be selected to ensure that Efficiency, Effectiveness, and Cost Effectiveness are all managed. […] KPIs can be either qualitative or quantitative. See also CSF
* **CSF (Critical Success Factor):** Something that must happen if a Process, Project, Plan or IT Service is to succeed. KPIs are used to measure the achievement of each CSF. For example, a CSF of “protect IT Services when making Changes” could be measured by KPIs such as “percentage reduction of unsuccessful Changes”, “percentage reduction in Changes causing Incidents,” etc.

## All about Metrics: Metrics should be SMART
* Critical Success Factors (CSFs): support business goals and objectives
  * Influenced by customers, competitors, suppliers, regulator
  * Defined by capabilities (abilities) and resources; market opportunities
  * Basis for competition
  * Will change over time
  * Proven, key factors determined by industry leaders
* Metric Types: (three types of metrics that an organization should collect to support CSI)
  * Technology Metrics: Performance and availability of CIs; measure Components and application
  * Service Metrics: are the results of end-to-end service, measured by component metrics
  * Process Metrics:
    * Quality, Performance, value, compliance of following the process
    * Performance of Service Management processes
    * CSFs, KPIs, and activity metrics: KPIs and metrics underpin each CSF
    * CSI uses these metrics as input in identifying improvement opportunities for each process

## Benchmark:
The recorded state of something at a specific point in time. A Benchmark can be created for a Configuration, a Process, or any other set of data. For example, a benchmark can be used in:
* Continual Service Improvement, to establish the current state for managing improvements
* Capacity Management, to document performance characteristics during normal operations

## PDCA (Plan-Do-Check-Act) | Deming Model:
A four-stage cycle for Process management, attributed to Edward Deming. Plan-Do-Check-Act is also called the Deming Cycle. The Deming Cycle can lead organizations to steady, ongoing improvement.
* PLAN: Design or revise Processes that support the IT Services
* DO: Implement the Plan and manage the Processes
* CHECK: Measure the Processes and IT Services, compare with Objectives and produce reports
* ACT: Plan and implement Changes to improve the processes

![image](https://user-images.githubusercontent.com/31813625/32953183-74991528-cb7d-11e7-94b1-017eac17f812.png)

## CSI Model: six basic steps
1.	What is the vision? (Business vision, mission, goals and objectives)
2.	Where are we now? (Baseline assessments)
3.	Where do we want to be? (Measurable targets)
4.	How do we get there? (Service & process improvement)
5.	Did we get there? (Measurements & Metrics)
6.	How do we keep the momentum going? (Ensuring that changes become embedded in the organization)

## IT backlog:
The accumulated, unfinished tasks built up within an IT department over time, which prevent IT from addressing new service requests in a timely manner.

## CSI Register: Quality backlog; centralized "improvement backlog"
* Listing of all improvement initiative organization-wide, categorized by size
* Single point of information to be used by Change, strategy meetings, SLA reviews, etc…
* Contents: Benefits, Prioritization, Customers/Services, Justification
* CSI Manager accountable and responsible
* SKMS is a very good place for us to keep and manage the CSI registers

## Continual Service Improvement – Value to the Business:
* Justified, gradual and continual improvement in service quality
* Continuous alignment between IT services and business requirements
* Gradual cost-effective improvements
* Monitoring and reporting used to identify improvements
* No area is “out-of-bounds” for improvement efforts


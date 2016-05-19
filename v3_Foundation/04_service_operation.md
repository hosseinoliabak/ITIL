# Service Operation:

## Event Management:
The process that manages events through their lifecycle with the aim of providing a sound basis for Operational Management
* Detects and analyzes events
* An Event is a detectable occurrence or change of state that has significance for IT Infrastructure Management or service delivery. An event may also mean an alert or notification created by a monitoring tool
* Classified the event as informational, a warning or exception
* Determines and initiates the appropriate response
* Provides and entry point (‘trigger’) for the execution of Service Operation processes

### Scope:
Automated monitoring and control of: The status of CIs; Environmental conditions (temperature, smoke); Software licenses; Security (Intrusion Detection); Normal CI activity.

### Event Management – Key Concepts
* Event: A change of state that has significance for the management of a Configuration Item or IT Service
  * Informational (regular operation), Warning (unusual operation), Exception (abnormality)
  * The term Event is also used to mean an Alert or notification created by any IT Service, Configuration Item or Monitoring tool
* Alert: A warning that a threshold has been reached, something has changed, or a Failure has occurred
* Incident: Some events are related to a Failure and will be reported as an Incident, which is handled by the Incident Management process

### Event Management Roles:
The service desk is typically not involved in Event Management, unless an event requires something that your organization has deemed within the scope of the service desk. IT Operations Management performs event monitoring and provides first-line support, typically from an IT Operations Bridge or a Network Operations Center (NOC). Technical Management and Application Management perform Event Management for the systems under their control; they also help resolve incidents and problems related to events. They also define what constitutes an event, and what control action must be taken if an event occurs.

  ![image](https://user-images.githubusercontent.com/31813625/32970895-d555f594-cbb8-11e7-9b02-83bdd880f8f0.png)

## Incident Management:
The process that manages all incidents through their lifecycle with the aim of minimizing the impact of any interruption to service

### Incident:
An unplanned event which causes (or may cause) and interruption to or a reduction in the quality of a service

### Incident Management:
* The primary goal of Incident Management is to restores service to user as quickly as possible and
  * Minimizes the adverse impact of failure on business operations thus
    * Ensuring that the best possible levels of service quality and availability are maintained
* Improves Customer and User Satisfaction
* Incident Management isn’t about making people happy; it’s about delivering what is stated in the SLA. Therefore, SLAs must be written well
* Incidents may be communicated:
  * Directly by users to a Service Desk
  * Via an Event Management tool
  * By technical staff
  * By 3rd parties
* All failures and questions or queries must be recorded
* The Service Desk ‘owns’ every Incident Management throughout its lifecycle
  * Service Requests are NOT incidents!
* A workaround is a means of reducing or eliminating the impact of an Incident (or Problem) for which a full resolution is not yet available.
* It is NOT aimed to automatically detect service affecting events

### Incident Management – Key Concepts
* Timescales: must be agreed for all incident-handling stages; how quickly an incident must be resolved
* Major Incidents: A separate procedure, with shorter timescales and greater urgency
* Status Tracking (Open, In progress, Pending, Resolved, Closed)
* Incident Models: Many Incidents are not new – they involve dealing with something that has happened before and may well happen again
  * Repeatable, predefined steps
  * Deal with a particular type of Incident
  * Ensure such incidents are handled in a predefined path to predefined timescales (e. g., Security Incidents, Capacity – or performance-related Incidents, etc…)
* Incidents Model elements:
  * Steps to be taken
  * Chronological order and dependencies of steps
  * Responsibilities (RACI chart)
  * Precautions to take before resolution
  * Timescales and threshold for completion
  * Escalation
* Service Request: Service Requests are not incidents; they are handled through Request Fulfilment process
* Root Cause: the underlying or original cause of an Incident or a Problem
* Root Cause Analysis (RCA): An Activity that identifies the Root Cause of an Incident or Problem. RCA typically concentrates on IT Infrastructure failures
* Diagnosis: A stage in the Incident and Problem Lifecycles. The purpose of Diagnosis is to identify a Workaround for an Incident or the Root Cause of a Problem
* Incident Routing: Escalation:
  * Functional: Passing an incident to people with a greater level of technical skill, more knowledge to resolve the incident to maintain customer satisfaction
  * Hierarchical: If the service desk discovers an incident that might breach an SLA, they must notify more senior levels of management about the incident, often to focus attention on an incident resolution
* Incident Activities

  ![image](https://user-images.githubusercontent.com/31813625/32971032-6fd5c018-cbb9-11e7-80a4-1d7f009528f8.png)

1.	**Identification:** Obviously, an incident cannot be investigated until you learn that an incident has actually occurred. Incidents can be identified via users, IT staff, or event monitoring tools
2.	**Logging:** Incidents must be fully logged and date/time stamped, regardless of whether they are raised through a Service Desk telephone call or automatically detected via an event alert
3.	**Categorization:** Categorization might be several levels deep (some organizations use a SCIM approach: System, Component, Item, and Module). Placing an incident in the proper category means grouping them by type, and possibly by which support group will address them. Proper incident categorization is important so Problem Management (and other processes) can find trends. If the call is determined to be a Service Request and not an incident, the service request is addressed by the Request Fulfillment process
4.	**Prioritization:** Prioritization determines the order in which the incident will be handled. The service desk agent, in consultation with the user, determines the priority based on impact and urgency. If it is a major incident, the appropriate major incident procedure is followed
5.	**Initial Diagnosis:** The service desk agent makes an initial diagnosis. Diagnostic scripts and known error information are valuable here. If possible, the service desk agent will resolve the incident and close the incident if the resolution is successful. If the service desk agent cannot resolve the incident, the user should be given the incident reference number (ticket number), and the service desk should escalate the incident so another team can find a resolution
6.	**Investigation and Diagnosis:** As the assigned technical group investigates and diagnoses the incident, a historical record of activities must be maintained in the incident record (ticket).
7.	**Resolution and Recovery:** When a resolution has been identified and tested, the recovery action completed, and the service has been fully restored to the user(s), the incident record must be marked as resolved. The resolving party must be sure to record in the incident record the steps taken to resolve the incident. When complete, the incident record is passed back to the service desk for closure
8.	**Closure:** The service desk (only) should check that the incident is fully resolved and that the users are satisfied and willing to agree the incident can be closed. Before closure, the service desk should also:
    * Double-check that the incident is in the proper category to ensure accuracy in reporting
    * Check to see whether they should ask the Problem Manager to open a problem record

### Incident Management – main Interfaces:
* SLM
* Information Security Management (ISM)
* Capacity Management
* Availability Management
* SACM
* ChM
* Problem Management: for very large, major, or recurring incidents
* Access Management

## Problem Management:
The process that manages all Problems through their lifecycle with the aim of preventing future Incidents from occurring and minimizing the impact of any that cannot be prevented.
* A problem is the unknown root cause of one or more existing or potential Incidents
* Known Errors have a known root cause
* Reduces the number and Impact of service failures
* Reduces the number of repetitive Incidents
* Reduces the frequency and cost of service Problems
* Improves the quality of Change and Release and Deployment Management
* Objectives
  * Prevents problems and resulting incidents (proactive problem management)
  * Eliminate recurring incidents
  * Minimize the impact of incidents that cannot be prevented
  * It is NOT aimed to restore service to a user
* Problem Management works with others to improve the availability and quality of IT services
* KEDB is available for us in SKMS
* A known Error is a Problem that has a documented root cause and a workaround; at any time after diagnosis of a Problem, a Known Error record (even though it may not yet be a permanent resolution) should be raised

### Problem Management – Key Concepts
* Known Error Database: KEDB stores knowledge about previous Incidents and Problems, resolutions and workaround; The Known Error record should hold exact details of the fault and the symptoms that occurred, together with precise details of any workaround or resolution action that can be taken to restore the Service and/or resolve the problem. The Known Error Database is owned by Problem Management; however, it is used by many teams, most notably the Service Desk.
  * Only the Problem Manager is allowed to populate the KEDB. Anyone can read from it, and anyone can suggest additions to it; however, to keep the integrity of the data high, only the Problem Manager can write to the KEDB. As the saying goes, “Too many cooks spoil the soup.”
* Problem Models
  * Many problems are unique and must be handled individually; however, it is conceivable that some Incidents might re-occur because of dormant or underlying Problems
  * Potential that repetitive incidents cannot be permanently fixed, be restored on a regular basis
  * Utilize the Known Error record but also develop a model for more efficient/speedier handling
* Two subprocesses of Problem Management (PM)
  * Reactive PM: Monitoring that takes action in response to an Event, though Problem Management is primarily a reactive process
  * Proactive PM: is initiated in Service Operation. looks for patterns of Events to predict possible future Failures. We would love to have more Proactive Problem Management than Reactive
* PM Activities

  ![image](https://user-images.githubusercontent.com/31813625/32971208-2564050c-cbba-11e7-8584-21b1e655dc83.png)

1.	Problem Detection: Problems can be detected through various means. ‘Top ten’ reporting, with drill-down capabilities to lower levels, is useful in identifying trends
2.	Problem Logging: all the relevant details of the problem must be recorded so that a full historic record exists. This must be date and time stamped to allow suitable control and escalation
3.	Problem Categorization: helps to ensure that the true nature of the problem can be easily traced and meaningful information can be obtained
4.	Problem Prioritization: frequency, impact of related incidents, severity of problem
5.	Problem Investigation and diagnosis: to diagnose the root cause of the problem. The CMS must be used to help determine the level of impact and to assist in pinpointing and diagnosing the exact point of failure. The Know Error Database (KEDB) should also be accessed and problem-matching techniques (such as key word searches) should be used to see if the problem has occurred before and, if so, to find the resolution
6.	Workarounds: In some cases, it may be possible to find a workaround to the incidents caused by the problem – a temporary way of overcoming the difficulties. Rebooting a PC when an application crashes is considered a workaround because the root cause of the word processing crash was not found, but this action enables the user to continue working. Workarounds for problems are documented as Known Error records in the KEDB
7.	Raising a Known Error Record: As soon as the diagnosis is complete, and particularly where a workaround has been found (even though it may not yet be a permanent resolution), a Known Error Record must be raised and placed in the Known Error Database – so that if further incidents or problems arise, they can be identified and the service restored more quickly
8.	Problem resolution: Ideally, as soon as a solution has been found, it should be applied to resolve the problem – but in reality, safeguards may be needed to ensure that this does not cause further difficulties
9.	Problem Closure: When any change has been completed (and successfully reviewed), and the resolution has been applied, the Problem Record should be formally closed – as should any related Incident Records that are still open
10.	Major Problem Review: After every major problem, while memories are still fresh a review should be conducted to learn any lessons for the future. The review should examine:
    * Those things that were done correctly
    * Those things that were done wrong
    * What could be done better in the future
    * How to prevent recurrence
    * Whether there has been any 3rd party responsibility and whether follow-up action needed

## Request Fulfillment:
This is a separate process from incident management and should be handled such as a different process
Service Request: A request from a User for information, documentation, advice, or for a Standard Change or for Access to an IT Service. For example to reset a password, additional software in a single desktop, or to provide standard IT Services for a new User. Many of these are actually small changes, low risk, frequently occurring, low cost, etc. Service Requests are initially handled by a Service Desk, and do not require an RFC to be submitted
Request Model: A predefined approach for handling a frequently occurring Service Request. This is similar to the concept of Incident Models
Request Fulfillment: Request fulfillment is the process for managing the lifecycle of all Service Requests
* Provides a channel for users to receive standard services; predefined approval and qualification process exists
  * It is NOT aimed for making sure ALL REQUESTS within an IT organization are fulfilled
* Provides information about services and how to obtain them (request can be just asking information)
* Source and supplies standard service components
* Maintain user/customer satisfaction through efficient / professional handling of all requests
* A Service Request is, often, a recurring request from Users which may be satisfied by making a Standard Change or by taking other pre-determined actions

## Access Management:
The process responsible for allowing Users to make use of IT Services, data or other assets while ensuring the security of those assets
* Can be initiated by a Service Request. Service Operation functions execute Access Management
* Grants authorized users the rights to use service and prevents access by those not authorized
* Executes policies and requirements defined in Security and Availability Management, actions completed by Technical and Application Management functions; managed by Service Desk
* May be known as Rights Management or Identity Management in some organizations
* We can define a group type of access instead of user type of access
* Access Management is the process that enables users to use the services documented in the Service Catalogue

### Access Management Key Terms:
* Access: Refers to the level and extent of a service’s functionality or data that a user is entitled to use
* Identity: Refers to the information about them that distinguishes them as an individual and which verifies their status within the organization. By definition, the identity of a user is unique to that user
* Rights: (sometimes also called “privileges”) Refer to the actual settings whereby a user is provided access to a service or group of services. Typical rights, or levels of access, include read, write, execute, change, delete
* Service Groups: Most users do not use only one service, and users performing a similar set of activities will use a similar set of services. Instead of providing access to each service for each user separately, it is more efficient to be able to grant each user—or group of users—access to the whole set of services that they are entitled to use at the same time
* Directory Services: Refers to a specific type of tool that is used to manage access and rights

## Functions
### Service Desk:
A free-standing function; the primary aim of Service Desk is to restore ‘normal service’ to users as quickly as possible. This could involve resolving an Incident, fulfilling a Service Request, or answering a query.
* Justification of a Service Desk
  * What is the alternative?
  * Customer service, SPOC
  * Efficiencies, reduced negative impact
  * Improved resource use
* The Service Desk is the SPOC between the users and internal and external IT service providers

#### Service Desk Objectives
* Logs, categorizes, and prioritizes Incidents and Service Requests
* Takes lifecycle ownership of all Incidents/Service Requests
* Provides 1st line support and resolve Incidents/Service Request where possible
* Escalate Incidents/Service Requests according to defined procedures
* Keep users informed of progress
* Closes all incidents, Service requests and other calls:
  * Check that the user is satisfied with the outcome
  * Check the incident categorization and correct it if necessary
  * Chase any outstanding details and ensure that the Incident Record is fully documented
  * Determine (in conjunction with resolver groups) whether it is likely that the incident could recur and decide whether any preventive action is necessary to avoid this. In conjunction with Problem Management, raise a Problem Record in all such cases so that preventive action is initiated
* Updates the CMS under direction and approval of SACM
* Conducts customer/user satisfaction surveys

#### Service Desk Organizational Structure:
* Local Service Desk: where a desk is co-located within or physically close to the user community it serves. Simply speaking, a local service desk has a one-to-one relationship between user locations and service desks - if your organization has 12 separate locations housing users, there will be 12 separate service desks, all working independently of each other. Local service desks usually are independently operated; each most likely will have its own freestanding CMS
* Centralized Service Desk: merging Service Desks into a single location. A centralized service desk has a many-to-one relationship between user locations and the service desk. If your organization has 12 separate locations housing users, you will have one service desk servicing them all with the same CMS
* Virtual Service Desk: the personnel may be spread or located in any number or type of geographical or structural locations. This brings in the option of ‘home working’, secondary support group, off-shoring or outsourcing, etc. Service desk personnel in this structure absolutely must use the same CMS
* Follow-the-sun: combining 2 or more geographically dispersed Service Desks provides 24-hr coverage
* Specialized Service Desk groups: Specialist group where calls can be routed directly
  * Speeds resolution
  * Allows staff gain necessary knowledge/skills

#### Support tools:
* Known Error Database: details of previous incidents/problems and their resolutions
* Diagnostic Scripts: to pinpoint the cause of failure
* Self-Help web Interface: FAQs, ‘How to do’ search, password change capability, software fix downloads (patches, service packs, bug fixe…), software repair
* Remote control: helpful for Service Desk Analyst to take control of user desktop

### Technical Management (TM):
The Function responsible for providing technical skills in support of IT Services and management of the Infrastructure.

#### Role:
* Custodian of technical knowledge and expertise related to managing the IT infrastructure
* Provide resources to support the ITSM lifecycle
* Guidance to IT Operations staff

#### Objectives:
* Provide input for a highly resilient, cost-effective technical topology
* Ensure adequate skills are available
* Provide swift, accurate diagnosis and resolution

### IT Operations Management:
The Function within an IT Service Provider that performs the daily Activities needed to manage IT Services and the supporting IT Infrastructure
#### Role:
* IT Operation Control: (“behind-the scene” tasks): Oversees the execution and monitoring of the operational activities and events in the IT infrastructure
  * Console management/Operation Bridge
  * Job scheduling
  * Backup and restore
  * Print and output management
  * Agreed maintenance activities
* Facilities Management:
  * Datacenters (e. g., Sticky Contamination Control Mats)
  * HVAC
  * Cabling
  * Recovery sites
  * Coordination of large scale consolidation projects
  * Management of outsources contracts

#### Purpose:
* Maintain infrastructure status quo
* Provide value-add; flexibility to adjust to new/changed business requirements
* Make a decision based on balancing stability and responsiveness upon a customer’s non-standard request

#### Objectives:
* Maintain day-to-day stability of operational processes
* Identify service improvements or reduced costs
* Quickly supply operations skills for failure diagnosis and resolution

### Application Management:
Responsible for managing the application throughout the lifecycle of a service.

#### Role:
* Custodian of the technical knowledge and expertise related to managing applications
* Ensures that the resources needed to design, build, transition, operate, and improve services are trained and available
* Balances resources and costs
* Adds value to the ‘build or buy’ discussion in Service Design phase

#### Objectives:
* Applications are well-designed, resilient, cost-effective
* Functionality is readily available to meet requirements
* Have necessary technical skills to maintain optimal performance
* Applies application skills to quality resolve failures

#### Organizational Structure:
* Works closely with Application Development but have different objectives
* Application Management follows the lines of Technical Management but with applications
* Application Development follows lines of business with emphasis on design/development of solutions

The service desk is a free-standing function; however, there is some overlap between the Technical Management, IT Operations Management, and Application Management functions






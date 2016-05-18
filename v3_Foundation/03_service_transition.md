# Service Transition:
## Service Asset & Configuration Management:
SACM provides a logical model of the IT infrastructure by defining and controlling service assets and components and maintaining accurate records in the Configuration Management System (CMS).
* Ensures IT assets are identified, controlled, cared for
  * Record, report, audit, verify CIs/assets, baselines, versions, components, attributes, relationships
* Every CI is a service asset but not every service asset is a CI
### SACM – Key Concepts
* A Service asset is anything that could contribute to the delivery of a service. They come in two flavors: Capabilities and resources
* A Configuration Item (CI) is any Component that needs to be managed in order to deliver an IT Service
  *	Attributes: name, location, version, serial number, owner, and Cost
  * Status (should be historical): Ordered, In production, Down for maintenance, In storage, Retired
  * Relationships: link between two CIs that identifies a dependency or connection between them; parent/child or peer-to-peer
  * Configuration baseline: can be used to enable the IT Infrastructure to be restored to a known Configuration if a Change or Release fails
* Configuration Management System (CMS): is a set of tools and databases that are used to manage an IT Service Provider’s configuration data; also includes information about Incidents, Problems, Known Errors, Changes, and Releases
  *	Configuration Management Database (CMDB): capture CIs and relationship between them
    * Verification and Audit is the only way to ensure CMDB integrity
  * Maintains the relationship between all service components, related Incidents, Problems, Known Errors, Changes, and Releases
  * Can determine the level of impact of a problem
  * May federate data from several Configuration Management Databases (CMDBs)
  * Links other data sources such as the Definitive Media Library, asset inventories, management information …
  * If an organization outsources its IT services, there is still a need for a CMS to control and report the infrastructure
  * **Configuration Model:**
    * is a mock-up model of a service or a group of CIs
    * Records the relationship between assets, infrastructure, and services
    * Change Management uses the Configuration Model to perform risk assessments and simulations when evaluating a change
    * Service Design uses it to plan and design new or changed services
    * Release and Deployment Management uses it to plan release and deployment packages and migrate service assets to different locations and service centers
    * Incident and Problem Management uses it to assess the impact and cause of outages
    * To plan technology refresh and software upgrades
    * To optimize asset utilization and costs, e.g. consolidate data centers, reduce variations and re-use assets.
  * When you have one clock, you know the time – if you have more than one, you are no longer certain
* SACM process formally ‘owns’ the DML
  * Definitive Media Library (DML): Official, approved versions of all electronic media CIs (software [both those developed in-house and purchased off the shelf], official versions of documentation, software licenses, activation keys, and so on) are securely stored in and released from the DML. The DML typically consists of one or more software file-storage areas, but a single logical storage area. All software in the DML is under control of Change Management and is recorded in the CMS. Only software from the DML is acceptable for use in a release
  * To clarify: The DML is officially maintained by Service Asset and Configuration Management, and it is controlled by Change Management. It is used primarily by Release and Deployment Management, as this is the only location from where software releases are deployed. It is part of the CMS.
### DML, CMDB, and CMS Relationship
* The CMDB contains information about CIs
* The DML contains the actual media CIs (the actual .exe, .msi, .pdf, and .doc files)
* The CI record for a given piece of software (for example) would contain the name of the software title, version information, and where the installation file is physically located. That physical location is where Release and Deployment Management will install from—the DML
* Both the CMDB and the DML are part of the larger CMS

### SACM Roles
The Configuration Manager is the process owner of the Service Asset and Configuration Management process. As the process owner, this person is responsible for the following tasks (DEMI):.
1.	<b>D</b>ocumenting the Configuration Management process.
2.	<b>E</b>ducating process participants on how to use the Configuration Management process correctly and ensuring that process participants are complying with the process.
3.	<b>M</b>easuring the success of the process against KPIs, CSFs, and other targets set.
4.	Continually <b>I</b>mproving the process. (This is done with input and assistance from the Continual Service Improvement Manager.)

Other SACM-related roles might be necessary, too:
* Configuration administrator/librarian
* CMS/tools administrator

The Change Manager also plays a role in SACM. The Change Manager ensures that after a change has been implemented, a list of the changed CIs gets populated into the CMDB/CMS. The Change Manager will not input this information into the CMDB/CMS himself, but instead will ensure that the Configuration Administrator/Librarian has done it correctly and in a timely fashion.

## Change Management:
Controls the lifecycle of all changes, enabling business benefit with minimal disruption to IT Services. (It is NOT the release and deployment process; it ensures that RDM has done its job).
* The most important thing to remember about Change Management is that this process is responsible for managing, coordinating, and facilitating changes. (Notice that this process does not include actually implementing the change.)
* Responds to Customer’s changing business requirements (Maximizes value; reduces change-related service failure, disruption, and rework)
* Responds to the business and IT request for change that will align services with the business need
* Remediation Plan (the Backout Plan): Mandatory for all changes. What to do if the change is unsuccessful. Changes should not be authorized unless the remediation plan is deemed solid by the appropriate change authority

### Change Management Vocabulary:
The Change Management process is one of the more vocabulary-intensive processes in ITIL. Because the Change Management process spans across the service lifecycle, the following terms will be used:
* Service Change: Often referred to as just a “change,” this word simply means to alter a CI in some way, whether it’s adding a CI, modifying a CI, or even removing a CI
* Request for Change (RFC): The form (electronic, paper, or otherwise) upon which the change is written. Submitting an RFC is how a change enters the Change Management process. For a major change with significant organizational and/or financial implications, a change proposal may be required
* Post-Implementation Review (PIR): A meeting held after the change implementation to determine its success. A PIR should be carried out to confirm that the Change has met its objectives, that the initiator and stakeholders are happy with the results, and that there have been no unexpected side effects. Sometimes the PIR is simply referred to as a “change review” in the ITIL books. You can use these terms interchangeably
* Change Advisory Board (CAB): The CAB is a committee of technical and business personnel that convenes to assist in the assessment, prioritization, and scheduling of changes
  * Assists Change Manager in risk and impact assessment of a RFC
  * Change Manager is responsible for chairing a CAB
  * Assists in priority and implementation schedule (Schedule of Change (SC))
  * Follows stated and agreed assessment criteria
  * Is made up of
    * Members: Change Manager (chair), Senior Application & Technical Manager, Senior Customer and User Representative, Service Level Manager, Problem Manager
    * Attendees: Finance Manager, Facilities Manager / Office Services, 3rd Party Suppliers
* Emergency CAB (ECAB):
  * Sub-set of the CAB; reviews changes that must be implemented faster than the normal change process
  * To assist Change Manager in evaluating emergency changes and to decide whether they should be authorized
* Change Authority: Both the CAB and the ECAB are advisory bodies only; it is up to the proper change authority (which might change depending on the size, complexity, and scope of a change) to provide the final stamp of approval. Change Authority is a role, person or a group of people that provides formal authorization for each change. Changes in a large enterprise that affect several distributed sites may need to be authorized by a higher-level change authority such as a global CAB or the Board of Directors

### Where do Changes Come From?
* An RFC document (a network admin needs to change a router configuration)
* A call to the service desk (a user would like a flat-panel monitor instead of a CRT monitor)
* A project initiation document (the finance department is implementing a new payroll system)
* A change proposal (for very large changes, such as outsourcing the service desk)

### Change Types:
* Standard: A pre-authorized change that is low risk, relatively common and follows a Procedure or Work Instruction – for example, a password reset for which we have a document. Some standard changes will be addressed via the Request Fulfillment process (part of Service Operation)
* Normal: A change that is not an emergency change or a standard change. Since it is not a standard or an emergency change, it is simply every other change and must be authorized
* Emergency: A Change that must be introduced as soon as possible; should be designed carefully and tested before use; Emergency changes are assessed by ECAB

### Change Model:
* Repeatable, predefined steps
* Deal with a particular type of change (Standard, Normal, Emergency)
* Ensures such changes are handled in a predefined path to a predefined timescale
* Remember that have a single change process but you can have multiple change models
* Basic Change Model Elements:
  * Steps to be taken
  * Chronological order & dependencies of steps
  * Responsibilities
  * Timescales & thresholds for completion
  * Escalation procedures
* Workflow tool: helps change management for managing changes

### 7 Rs of Change Management:
* Who RAISED the change?
* What is the REASON for change?
* What is the RETURN required from the change?
* What are the RISKs involved in the change?
* What RESOURCES are required to deliver and support the change?
* Who is RESPONSIBLE for the build, test, and implementation of the change?
* What is the RELATIONSHIP between this change and other changes?

Answer to these questions enables the change authority to assess and evaluate changes based on priority, risk, benefits, and costs.

### Activities:
* Step 1: Create and record RFCs: RFCs can come from any person or team in the organization, whether from the business side or from IT
* Step 2: Review RFC: In this step, the change manager reviews the RFC to make sure the form is filled out correctly, has the required information, and so on. The change is also logged in the CMS
* Step 3: Assess and evaluate the change: The change manager determines the appropriate level of change authority needed to authorize the change, and then decides who should be involved in CAB given the type of change. Next, usually with assistance from the CAB, the change is assessed and evaluated for its cost, benefits, and potential impact to both the business as well as other IT systems
* Step 4: Authorize the change: The change is authorized by the appropriate change authority, and the initiator of the Request for Change is notified
* Step 5: Coordinate Change implementation: This is where the Change Management process manages/coordinates/oversees what is built, tested, and implemented by Release and Deployment Management
* Step 6: Review and Close the Change: After the change has been implemented by the Release and Deployment Management process, the Change Manager reviews the change and its change documentation, and then closes the change record in the CMS when all actions are completed

![image](https://user-images.githubusercontent.com/31813625/32970056-61cc081e-cbb5-11e7-9b08-ab597d570d53.png)

### Main interfaces between ChM and other processes:
* Service Asset & Configuration Management (SACM)
* Release and Deployment Management (RDM)
* Transition Planning & Support (TPS)
* Change Evaluation
* Problem Management

### Remember
* Change Management manages and coordinates the change. Accountable for the success of all changes
* Release and Deployment Management builds, tests, and implements the change. Responsible for the success of all changes
* Service Asset and Configuration Management tracks the changes to the CIs in the CMDB/CMS. Consulted and Informed of all changes

### Change & Service Asset and Configuration Management
![image](https://user-images.githubusercontent.com/31813625/32970126-a6a03d8e-cbb5-11e7-8994-53de81b54ab8.png)

## Release and Deployment Management:
Builds, tests, and delivers the capability to provide the services specified by Service Design and that will accomplish the stakeholders’ requirements and deliver the intended objectives; hands over to Service Operation.
* Deploys releases into production
* Establish effective use of the service in order to deliver value to the customer
* RDM is where the activities of Service Transition “touch” and affect the customers and users

### Scope:
Includes processes, systems, functions to build, test, deploy a release.

### RDM – Key Concepts:
* Release: A collection of hardware, software, documentation, Processes or other Components required to implement one or more approved Changes to IT Services.
*Release Unit: Components that are normally released together. A release unit typically includes sufficient components to perform a useful function. For example, one Release Unit could be a Desktop PC, including Hardware, Software, Licenses, Documentation, etc.
* Release Package: one or more release unit(s)
* Definitive Media Library (DML): Backups are never stored in the DML
* Release Policy: document
* Defines the release units/packages for a service
  * Specifies identification, numbering, and naming conventions
    * Major – new functionality; 1.0, 2.0, etc…
    * Minor – small enhancement; 1.1, 1.2, etc…
    * Emergency – correct known error/high priority business requirements; 1.1.1, 1.1.2, etc…
  * Roles & responsibilities (test, build, deploy…)
  * Frequency
  * How changes are accepted/grouped into a release
  * Automation mechanism (build, test, distribute, install)
  * Configuration baseline
  * Entry/exit criteria and acceptance for each ST stage
  * Criteria and authorization for Early Life Support (ELS provides resources to resolve operational and support for a new or Changed IT Service for a period of time after it is Released)

### Four Phases of RDM:
(1: Planning, 2: Release Build and Test, 3: Deployment, 4: Review & Close)

<img src="https://user-images.githubusercontent.com/31813625/32970321-84649f02-cbb6-11e7-9dd0-e26ffe41bb11.PNG" width="590" height="256" />

## Knowledge Management:
Gathers, analyzes, stores, and shares knowledge and information within an organization.
* The goal of Knowledge Management is to ensure that decision-makers have the ability to make informed decisions based on accurate data and careful analysis of trends
* Improves decision-making by ensuring reliable and secure information is available throughout the service lifecycle
* Improves the efficiency by reducing the need to rediscover knowledge
* Ensures the right information is delivered to the appropriate place/person at the right time enabling informed decision-making
* Must clearly define information that is under KM control and purview
* Knowledge Management uses a structure we call Data – Information – Knowledge – Wisdom (DIKW)
  * Data: discrete facts about events
  * Information (Who, What, When, Where?): provides context to data
  * Knowledge (How?): puts information in ‘ease of use’ form for decision making; includes experience, ideas, insights, value & judgments
  * Wisdom (Why?): applies knowledge in the context in which it will be used; provides strong common-sense judgment; CANNOT be provided by a tool

### SKMS:
Covers a much wider base of knowledge than the CMS or CMDB
* The experience of staff
* Records peripheral matters (e.g., weather, user numbers, behaviors, etc…)
* Suppliers’ and partners’ requirements, abilities, and expectations
* Typical and anticipated user skill levels

## Transition Planning & Support:
Plans and coordinates the resources to ensure that the requirements of Service Strategy encoded in Service Design are effectively realized in Service Operations.
* Helps Service Providers to deploy Services into the live environment.
* Establishes new or changed services into supported environments within the predicted cost, quality, and time estimates
* Plans appropriate capacity and resources for a release (Does NOT plan build, test, or implement activities)
* Plans changes required to ensure the integrity of customer assets, service assets and configurations
* Ensures Service Transition issues, risks and deviations are reported to appropriate decision makers
* Ensures the adoption of a common framework to improve integration planning and coordination activities













# Getting Started

HealTheta helps you to create health care applications and enables interoperability between various healthcare systems using FHIR API standard. It is believed that the future of healthcare applications will interface using fast health care interoperability resources. FHIR standardizes a RESTful interface for hundreds of clinical objects spanning Patients, Claims, Providers, Medications, etc. On top of this, HealTheta enables apps to plug into hundreds of health system locations using OAuth2 and EHR standards, so teams can embed their app within the EHR and authorize access to patient data. Typical standardization of this technology involves many facets including data structure, version tracking, methods of autorization, search APIs. Additionally HealTheta enables FHIR provenance on blockchain based ledger technology. HealTheta's purpose and objective is to help app developers a jump start by providing all functionalties such as, data storage, Application Programming Interfaces, Privacy and Security so the team can focus on adding value to their end product,

## Why Use HealTheta ?
HealTheta's vision of substitutable healthcare applications holds many benefits for app developers, healthcare providers, patients, healthcare institutions and public health, Those are,

### Health Care Providers
- Apps empower users, rather than only technology vendors or government committees, to decide which health IT products are beneficial and valuable
- Add new capabilities to existing systems, for example to visualize risks, trends, and trajectories
- Integrate new data into systems, mashing up clinical records with external data sources and incorporating new flows of data from sensors, devices, and patient reports

### Health Care Institutions
- Improve return on EHR investment by streamlining internal EHR customization projects
- Simplify the integration of best of breed components into existing systems
- Ability to easily draw on a library of innovate apps encourages market competition on quality, cost, and usability

### Public Health
- Apps can transfer ideas, functionality, and workflow all in one package – a good app, distributed widely, could reshape practice overnight
- Decision support can be updated without the need to customize for each EHR, supporting rapid response during outbreaks and as guidelines change

* * *

# Architecture

From Architecture and Design perspective we focused on following factors which affects the system configuration, performance , quality ,privacy and security as the major architecture design drivers of a scalable secure health care services platform.

- It should be able to host on a multi-tenant SAAS platform
- Only Authorized applications and users should access the health care service
- It should be client agnostic; As it should support access over all available client access verticals, PC, mobile and tablets
- It should be able to share resource based on a consent directive management model
- And last but not the least, It should be easy to integrate and easier to enable multi-tude of agnostic applicatinos around all available horizontals.

The requirements of health care service platform include CDS services, order entry and display, immunization management, service availability checking,account management, patient information management, and appointments/admission scheduling for small- and mid-sized hospitals and clinical data assesment and analytics.

![Branching](https://user-images.githubusercontent.com/43714632/47506914-b6e1b100-d88e-11e8-9c59-8a9531a79412.jpg)

## Resource Engine
The Resource Engine is built on pico-services architecture on top of micro-service granularity. The entire design and development of resource engine is built keeping in security and privacy in mind. We believe in building security from ground up than building security around it. To facilate security from ground up we have used following modern hype factors in to our design
- Object level security granularity ( pico-services)
- Consent based acces management in-built within each resources
- Edge-Gateway to provide additional higher level of security and routing
- Granual management of access on object level

## Privacy & Security Engine
Privacy and Security Engine provide basic security services for our resource and intelligence engine. It is encompassed of three components. 
### Consent Directive Management Service
Consent directive management microservice allows patients to determine, through an online consent process, which health information they would like to share and not share with their primary and specialty health care providers. Consent Dirctive Management service is built keeping in following in mind,
- Developed to meet the need for patients to have meaningful choices to share their protected behavioral healthcare information
- Should be able to integrate with existing electronic health record (EHR) and health information exchange (HIE) systems using interoperability standards
- Supports federal and state requirements related to protected health information, such as 42 CFR Part 2
- Puts control of health information exchange in the hands the person who has the right to decide who has access to his or her data: the patient

### Identity & Access Control Service
<TODO>

### Redact & Anonymity Service
<TODO>

## Inteligence Engine

* * *

# API
## Foundation API

| Module        | Description          | Detail |
|:-------------|:------------------|:------|
| CodeSystem           | CodeSystem API | [here](./another-page.html).  |
| ValueSet | Value set API   | [here](./another-page.html).  |
| Consent           | Consent API     | [here](./another-page.html).   |


## Base API

| Module        | Description          | Detail |
|:-------------|:------------------|:------|
| Patient           | Patient API | [here](./another-page.html).  |
| Pracitioner | Practitioner API   | [here](./another-page.html).  |
| Organization           | Organization API     | [here](./another-page.html).   |
| HealthcareService          | HealthcareService API | [here](./another-page.html). |
| Appointment          | Appointment API | [here](./another-page.html). |
| Schedule          | Schedule API | [here](./another-page.html). |
| Slot          | Slot API | [here](./another-page.html). |
| Encounter          | Encounter API | [here](./another-page.html). |

## Clinical API

| Module        | Description          | Detail |
|:-------------|:------------------|:------|
| AllergyIntolerence           | AllergyIntolerence API | [here](./another-page.html).  |
| Condition | Condition API   | [here](./another-page.html).  |
| Procedure           | Procedure API     | [here](./another-page.html).   |
| Observation          | Observation API | [here](./another-page.html). |
| DiagnosticReport          | DiagnosticReport API | [here](./another-page.html). |
| MedicationRequest          | MedicationRequest API | [here](./another-page.html). |
| Medication          | Medication API | [here](./another-page.html). |
| MedicationStatement          | MedicationStatement API | [here](./another-page.html). |
| CarePlan          | CarePlan API | [here](./another-page.html). |

## Financial API

| Module        | Description          | Detail |
|:-------------|:------------------|:------|
| Account           | Account API | [here](./another-page.html).  |
| Coverage | Coverage API   | [here](./another-page.html).  |
| Claim           | Claim API     | [here](./another-page.html).   |
| PaymentNotice          | PaymentNotice API | [here](./another-page.html). |



* * *



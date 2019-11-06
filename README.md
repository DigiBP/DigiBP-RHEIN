# DigiBP Camunda Template

[![License](http://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)
[![Deploy to Heroku](https://img.shields.io/badge/deploy%20to-Heroku-6762a6.svg?longCache=true)](https://heroku.com/deploy)

## Authors
Sebastian Kluthe

Teyfik Agac

Pamela Streisguth

## Description
### Employee recruitment in  a company 
The recruitment of new employees is of strategic importance for a company. Finding the best candidate for the position, that also fits to the company culture is a challenge. Several stakeholders are in involved in the recruitment process, such as employees from the human resource (HR) department and the hiring department, where the open position is located. The below process model shows the recruitment process of the company.

### Strategic Process Model
The process starts at the hiring department, where need for support was identified. The line manager defines the position and outlines the relevant skills needed for the job. Afterwards HR creates the job advertisement. After creation, the advertisement is reviewed by the hiring department. Afterwards will be decided, if the advertisement needs to be reworked or if the advertisement is accepted. If the advertisement is accepted, it will be published and becomes visible for applicants. The applicants are now able to submit their applications. Having received the applications, possible candidates will be identified. HR will check documents for completeness. If there are missing documents, HR will ask applicants for missing documents. The applicants will hand in missing docs, which will again collected and checked  by HR. If the resumé is fitting for the open position, a first interview will be initiated with the applicant. If the applicant still matches the job profile a second interview may be scheduled. Afterwards a candidate evaluation will be done. If the candidate sill is a fit for the position, contract negotiations will start. Depending on the outcome, a contract is signed or another applicant may be considered. Once the hiring process is over on boarding activities can be planned and executed. 

The aim of the project is to improve the overall process by applying optimization methods and where deemed useful implementation of automated, digital processes.

Next steps for the project will involve process optimization and tool selection. A detailed implementation plan will depend on those steps.

### Steps of the model

|Id|Title|As-Is|To-Be|Used Tools|
|---|---|---|---|---|
| 1 | Create job advertisement | The department identifies a need for support in a specific area and passes information on the position to the HR. The HR creates a specific advertisement for the position and consults the department. | The department identifies a need for support in a specific area and passes specifically predefined information to the HR. The HR takes said information and puts it in a standardized format.  |   |
| 2 | Publishing the job advertisement | When HR and department agree on the advertisement, the ad gets published on the company-website. | Consulting the department is not necessary anymore due to standardization of the job advertisements. The advertisement gets published automatically on multiple platforms (Xing, LinkedIn, etc.). | Integromat (LinkedIn-tool) |
| 3 | Collect documents from applicants | HR gets contacted by applicants and checks manually every application for missing documents. If anything is missing, applicants get manually informed to either send missing docs. or be declined for further consideration. | Applicants have to fill in a predefined/standardized form, disabling the possibility to hand in incomplete applications. |   |
| 4 | Identifying suitable candidates | HR checks each application for specified skills and experience. If the applicants meet defined requirements, applicants are considered, if applicants do not meet reqs., a rejection is sent. | Process gets split in two parts: 1. Automatically running a keyword-search program on the applications. For each important/required keyword applicants get points assigned. Depending on count, applicants get either rejected or stay in consideration. 2. Manual check of applications which achieved a specific point sum in step 1. Applicants fulfilling requirements stay in consideration. |   |
| 5 | Interview 1 |   | Predefined form asking for specific information about the applicant to enable comparing candidates. |   |
| 6 | Interview 2 |   | Predefined form asking for specific information about the applicant to enable comparing candidates. |   |
| 7 | Candidate evaluation | HR and the department exchange information and opinions on each candidate to decide which candidate will get the job offer. | Process cannot be automated due to important factors like suitability in department team and others which are subjective. |   |
| 8 | Contract negotiation | HR informs candidate of the decision. Candidate gets a wage offer depending on the rewarding class of the position. | Candidate gets an offer depending on market averages. These averages are calculated by automated online searches on accessible platforms to enable competitive offers for the market. (LinkedIn, Xing, other platforms displaying income averages). |   |
| 9 |  Hiring | HR invites candidate to sign paperwork and finish employment process. | Process cannot be automated due to importance of candidate cooperation. |   |
| 10 | On-Boarding | Candidate gets information about specific tasks, environment and workflows of the department/position acquired.  | Cannot be automated despite automatically handing information via e-mail/mail to candidate. |   |

#### General automation changes
Over the whole employment process the information traffic between company and applicants (invitations, rejections, etc.) will get automated/standardized. Forms will be defined to enable standardized communication.


#### Tool analysis 

To automate the interview process and improve the interview experience, different tools with specific characteristics and use cases are under analysis. Since the tool selection was not yet done, it was not yet included into the process model.


| Tool  | Use case | 
| --- | --- |          
| `LinkedIn` | Job Posting | 
| `Calendar` | Timeline management, Internal scheduling, Reminders | 
| `VC and chat tools` | Virtual interviews|
| `Databases`| Aggregation tool, Retention for candidates for future positions|
| `Forms` | Short questionnaires instead of motivation letters |
| `Mail` | Notification of stakeholders |
| `Maps` | Interview location |



## Maintainer
- [Digitalisation of Business Processes](https://github.com/digibp)

## License

- [Apache License, Version 2.0](https://github.com/DigiBP/digibp-archetype-camunda-boot/blob/master/LICENSE)

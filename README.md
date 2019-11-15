# Recruitment Process at worXart

[![License](http://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)
[![Deploy to Heroku](https://img.shields.io/badge/deploy%20to-Heroku-6762a6.svg?longCache=true)](https://heroku.com/deploy)

# About worXart
worXart is a Swiss small and medium-sized software developing firm with 60 employees. Due to its size and limited resources available, worXart aims to automate some of their major business processes. One of the processes it wants to automate, is the hiring process. 


## Description
### Employee recruitment in  a company 
The recruitment of new employees is strategicaly important for a company. Finding the best candidate to fill a vacancy, that also fits the prevailing company culture is a challenge. Several stakeholders are in involved in the recruitment process, such as employees from the human resource (HR) department and the hiring department, where a job opening has to be filled. The below process model shows the recruitment process of the company.

### Strategic Process Model
The process starts at the hiring department, where a job vacancy was identified. The line manager raises a recruitment request, defines the position and outlines the job requirements and skills needed to perform the job. Later on, HR creates the job advertisement. Afterwards, the advertisement is reviewed by the hiring department. It will be decided, if the advertisement needs to be reworked or if the advertisement is accepted. If the advertisement is accepted, it will be published and becomes visible for applicants on the company's website and LinkedIn. The applicants are now able to submit their applications. After having received the applications, potential candidates will be identified. HR will check the documents for completeness. In case of missing documents, HR will ask the applicants for the missing documents. The applicants will hand in missing documents, which will again be collected and checked  by HR. If the resumé fits the open position, a first interview will be initiated. If the applicant still matches the job profile, a second interview may be scheduled. Later on, a candidate evaluation will be done. If the candidate sill is a fit for the vacancy, contract negotiations will start. Depending on the outcome, a contract is signed or another applicant may be considered. Once the hiring process is over the onboarding activities can be planned and executed. 

![20191114_Strategic Process Model](https://user-images.githubusercontent.com/56949532/68846166-eac38a80-06cc-11ea-84c4-1fadde443abb.png)

The aim of the project is to improve the overall process by applying optimization methods and where deemed useful implementation of automated, digital processes.

Next steps for the project will involve process optimization and tool selection. A detailed implementation plan will depend on those steps.

### Steps of the model

|Id|Title|As-Is|To-Be|Used Tools|
|---|---|---|---|---|
| 1 | Create job advertisement | <li> The department identifies a need for support in a specific area and passes information on the position to the HR <li> The HR creates a specific advertisement for the position and consults the department | <li> The department identifies a need for support in a specific area and passes specifically predefined information to the HR <li> The HR takes said information and puts it in a standardized format.  |   |
| 2 | Publishing the job advertisement | <li> When HR and department agree on the advertisement, the ad gets published on the company-website | <li> Consulting the department is not necessary anymore due to standardization of the job advertisements <li> The advertisement gets published automatically on multiple platforms (Xing, LinkedIn, etc.). | Integromat (LinkedIn-tool) |
| 3 | <li> Collect documents from applicants | <li> HR gets contacted by applicants and checks manually every application for missing documents <li> If anything is missing, applicants get manually informed to either send missing docs. or be declined for further consideration. | <li> Applicants have to fill in a predefined/standardized form, disabling the possibility to hand in incomplete applications. |   |
| 4 | Identifying suitable candidates | <li> HR checks each application for specified skills and experience <li> If the applicants meet defined requirements, applicants are considered, if applicants do not meet reqs., a rejection is sent | <li> Process gets split in two parts: 1. Automatically running a keyword-search program on the applications. For each important/required keyword applicants get points assigned <li> Depending on count, applicants get either rejected or stay in consideration <li> 2. Manual check of applications which achieved a specific point sum in step 1 <li> Applicants fulfilling requirements stay in consideration. |   |
| 5 | Interview 1 |   | <li> Predefined form asking for specific information about the applicant to enable comparing candidates. |   |
| 6 | Interview 2 |   | <li> Predefined form asking for specific information about the applicant to enable comparing candidates. |   |
| 7 | Candidate evaluation | <li> HR and the department exchange information and opinions on each candidate to decide which candidate will get the job offer. | <li> Process cannot be automated due to important factors like suitability in department team and others which are subjective. |   |
| 8 | Contract negotiation | <li> HR informs candidate of the decision <li> Candidate gets a wage offer depending on the rewarding class of the position. | Candidate gets an offer depending on market averages <li> These averages are calculated by automated online searches on accessible platforms to enable competitive offers for the market. (LinkedIn, Xing, other platforms displaying income averages). |   |
| 9 |  Hiring | <li> HR invites candidate to sign paperwork and finish employment processes | <li> Process cannot be automated due to importance of candidate cooperation. |   |
| 10 | On-Boarding | <li> Candidate gets information about specific tasks, environment and workflows of the department/position acquired  | <li> Cannot be automated despite automatically handing information via e-mail/mail to candidate. |   |

#### General automation changes
Over the whole employment process the information traffic between company and applicants (invitations, rejections, etc.) will get automated/standardized. Forms will be defined to enable standardized communication.


#### Tool analysis 

To automate the interview process and improve the interview experience, different tools with specific characteristics and use cases are under analysis. Since the tool selection was not yet done, it was not yet included into the process model.


| Tool  | Use case | 
| --- | --- |          
| `LinkedIn` | Job posting | 
| `Calendar` | Timeline management, internal scheduling, reminders | 
| `VC and chat tools` | Virtual interviews|
| `Databases`| Aggregation tool, retention for candidates for future positions|
| `Forms` | Short questionnaires instead of motivation letters |
| `Mail` | Notification of stakeholders |
| `Maps` | Interview location |

## Authors
Sebastian Kluthe

Teyfik Agac

Pamela Streisguth


## Maintainer
- [Digitalisation of Business Processes](https://github.com/digibp)

## License

- [Apache License, Version 2.0](https://github.com/DigiBP/digibp-archetype-camunda-boot/blob/master/LICENSE)



*NOTE:*

*The project is practice for the backend development tools PHP and SQL.*

*As of July 2nd, 2021, the Incident Response Form repository is only holds html and css files. PHP and SQL files will come in the coming weeks. Due to Github Pages only supporting static webpages and a lack of a host domain, a video demo will be out shortly after the project is finished.*

-----------------------------------
Basic-Incident-Response-Form
===================================

DEMO: [FORTHCOMING]

## How the Basic-Incident-Response-Form Works
-------------------
Using HTML, CSS, SQL, and PHP, the form will track incidents as they occur. When an incident is declared, it is assigned a unique identifier and it is recorded in a database. For each incident, the incident number, a type of incident (chosen from a dynamically changing list), the date it was created, an incident state ('open', 'closed', 'stalled'), and a list of free-form comments is maintained. Associated with each comment is the name of the handler who wrote it.

In addition, associated with each incident could be any number of people (last name, first name, job title, email address), and any number of IP addresses. With each IP address or each person, the handler can record a reason for the address association.

Incident responders are able to query the database by incident number and receive a report containing the full history of a given incident. Free form comments are sorted from most recent on top, to oldest on the bottom. In addition, incident responders are able to record new incidents, change the state of incidents, add comments, and/or add and remove people and IP addresses.

To facilitate information sharing, the incident tracking system can xport each incident in a standard incident exchange format and send it via email. Likewise, other teams may send incident-related information via email to the CSIRT operating this application. When that happens, each report received will trigger a new incident being recorded.

All updates to an incident are recorded as free-form comments to the incident. All use of the system is subject to authentication via an external single sign-on system.

*NOTE: Incidents 1, 3, and 4 are pre-made. Comment ID’s are displayed when responding to incidents and should be used to gauge what comments to remove.*

PEOPLE IN THE DATABASE
----------------------------------------
- John Smith
- Robert Shire
- Doris Tierney
- Jack Svane
- Rose Anderson
- Donna Anderson
- Chris Johnson
- Grace Enquist
- Katherine Fitzgerald
- Nicole Walsh

*NOTE: Their jobs are listed in the ‘final.sql’ file for further testing.*

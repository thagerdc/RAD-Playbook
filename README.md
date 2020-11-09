# REMOTE APPLICATION DEVELOPMENT PLAYBOOK
Macro Solutions' Remote Application Development Playbook
Macro Solutions’ Remote Application Development (‘RAD’) Playbook provides guidance and processes needed to efficiently and effectively develop and deliver products that meet our customers’ needs. The Playbook enables our team to “hit the ground running,” providing significant benefit to our customers by increasing program management efficiency, decreasing program time and cost, reducing execution risks, and streamlining delivery.

### KEY PRACTICES

- Connectedness is critical – Emphasize the importance of video and being present.  Video meetings are not a time for multi-tasking.
- Building trust takes commitment – Trust is easier to build if teams have been working with the customer for some time, especially if they have met in person. For team members who have not met, trust may be low. Ensure team members have some time to interact socially (via video) as this will build a human connection and increase trust and productivity.
- Embrace ﬂexibility – Remote support teams must work harder to remain connected and will often need to work early or late in the day to connect with colleagues. Find ways to incentivize flexible behaviors.
- Good audio etiquette is vital – Practice good meeting etiquette: remain on mute if you have background noise, don’t hog the microphone, take turns to speak (use the virtual “raise hand” in tooling that supports it), be polite, and keep an eye on chat for team members raising points to discuss.  Use earbud-style or wired headsets for best sound quality.

### THE PLAYS

Designed to address the execution process, this Playbook offers program managers and software engineers information on how Federal Agile Digital Services are integrated with remote development. Fundamentally, this Playbook provides the overall structure for how to implement Macro’s Remote Application Development processes and provides practical instructions to execute projects, filling in the gaps in the absence of any customer-provided methodology or tooling. The following plays are core to this approach and are covered in more detail in the following pages.

1.	Remote Infrastructure
2.	Virtual Communications
3.	Managing Stakeholder Expectations
4.	Ways of Working
5.	Supporting People
6.	Digital Service Adoption

*-----------------------------------------------------------------------------------------------------------------------------------------------------------*

## 1. REMOTE INFRASTRUCTURE
The first component to support a remotely connected team is to ensure personnel have the necessary technology and hardware infrastructure in place to support the customer.

WHAT’S NEEDED
Item	Description	Suggested Tools & Practices (Absent of Customer-Defined)
Hardware	|	Laptop (or tablets), monitors, webcam, mic and speaker setup that works well enough for team collaboration.	Laptop + Earbuds with noise cancellation (tablets for interactive design sessions)
Constant Connectivity	|	All team members are expected to be available during core work hours and customer-agreed upon hours. Perform network checks on internal networks daily, cell phone connectivity and home network (when permitted). 	
VPN	|	Set up VPN, if required. Access has been tested and works. Backup plan in place if VPN fails (e.g. download the code if source control is unavailable).	Hot spot for phone connectivity
Security	|	Process in place to meet federal client security requirements (e.g. request access, user ID etc.). Team members are not relying on teammates for systems access.	In absence of GFE - hard drive encryption, device hardening, SSL, MDM, Password managers, Multi-factor authentication
Source control	|	The team can log on and use the source control tool (e.g. GitHub works on VPN). Make sure all your privately hosted or government services are available over VPN or other means.	GitLab, GitHub
Build pipelines & automation	|	The team can access and run the build and automation tools eﬀectively.	CircleCI, AWS CodePipeline, Google Cloud Build
Environments	|	Team members can access test environments and databases remotely.
|	Production support can continue remotely, including access to logging and monitoring, deployments.	AWS, Azure

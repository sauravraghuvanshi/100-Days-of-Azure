# 100-Day-of-Cloud
In this Repository, I am going to mention my Cloud Learning for Next 100 Days

# Target-1 (To Clear AZ-400 Certification Exam) 
## Started preparation for Microsoft Azure DevOps Solution(AZ-400)

## Day-1:-

### Skilled Measured During the Exam:-
* Devlop a Site Reliability Engineering Strategy
* Devlop an instrumental strategy
* Manage  source control
* Facilitate communication and collaboration
* Define and implement continious integration
* Define and implement continious deployment
* Devlop a security and compliance plan

### Understanding DevOps:-
* What is DevOps?
* The goal of DevOps
* The Culture change that is involved
* The different phases(Plan, Code, Build, Testing, Release, Deploy, Operate, Monitor)

### The different DevOps tools:-
* Your Planning tools(e.g. Azure Boards, Trello, Atlassian)
* Your issue tracking tools(e.g. Atlassian JIRA, Azure Boards, and Pivotal Tracler)
* Your source control tools(e.g. Git-GitHub/Azure Repos, Team Foundation Server, Subversion)
* The Continious Integration tools(e.g. Jenkins, Azure Pipelines, Travis CI)
* The Continious Deployment tools(e.g. Octopus Deploy, Azure Pipeline, AWS CodeDeploy)
* The Monitoring and Logging tools(e.g. ELK stack, Azure Monitor, Datadog)

## Section-1: Devlop an Instrumental Strategy:-

## Day-2:-

### Creating a resource-Azure Virtual Machine
* Created 2 Virual Machine
* One is Windows Server 2019 datacenter and second is Linux Vitual Machine.
* In Windows server we allowed RDP and HTTP port and then installed web Server on it from "Add role and feature section"
* In Linux virtual machine we login through PuTTY and then installed inginx using the command "sudo apt-get install nginx"

## Day-3:-

### Creating a resource-Azure storage account
* Created a storage account account in Azure.
* Used Azure Storage explorer, which is a free software that use to upload and retreve data on Azure storage. 

### Azure Monitor-Metrices
* Learned about Azure Monitor service
* Worked with metrices in azure monitor.
* Azure motitor is a monitoring service that can be used for collecting, analysing and acting on telemetry for cloud and on-premises environment.
* There are many tools available in Azure Monitor.
* We can detect and diagnose issues across application and dependencies with **Application Insights**.
* We can store and drill into monitoring data using **Log Analytics**.
* We can able to create visualization using **Azure Dashboard** and **Workbooks**
* The data collected by Azure Monitor is segregated into matcices and logs.
* Metrices are point in time values.
* Logs are recorded that can reside in a **Log Analytics workspace**.
* The Azure Monitor service uses a version of the kusto query language that can be used in the Azure Data explorer to build queries on your data.
* **Azure Monitor collects data in the following tiers**
  - Application monitoring data
  - Guest OS monitoring data
  - Azure resource monitoring data
  - Azure subscription  monitoring data
  - Azure tenent monitoring data

* **Note**: When we go in Azure Monitor-> Matrix Section, it will ask for scope of which we want to access the data.

## Day-4:-

### Azure Monitor-Activity Logs:-
* In this we learned about Activity Logs with Azure Monitor.
* Azure Activity log stores all Controlled Plane Activity(e.g. someone created VM or someone regenerate the key for storage account. We have the log and they are Contolled Plan Activity)
* It is like the recording of all of the administrative action.
* We can able to stream our activity log into storage account or log analytics workspaces from Diagnostic settings.

### Azure Monitor-Alerts:-
* We have to understand what are alerts in the Azure Monitor Service.
* How to work with alerts in the Azure Monitor service.
* We have to define alerts in Azure Monitors.
* These alerts can be used to notify you whenever any condition are met in the monitoring data.
* We can able to create alerts based on the below monitoring data source:-
 - Matrices Values
 - Log serach queries
 - Activity log events
 - From the health of the underlying Azure platform
 - From tests made for website availability

* Understand the defination of Target resource, Signal, Criteria, Action.
* **Steps to create alert rule**: Select Resource-> Condition(Matrices, Activity Log)-> Action-> Alert rule details 

## Day-5:-







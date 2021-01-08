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

# Section-1: Devlop an Instrumental Strategy:-

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
* **We can able to create alerts based on the below monitoring data source**
  - Matrices Values
  - Log serach queries
  - Activity log events
  - From the health of the underlying Azure platform
  - From tests made for website availability

* Understand the defination of Target resource, Signal, Criteria, Action.
* **Steps to create alert rule**: Select Resource-> Condition(Matrices, Activity Log)-> Action-> Alert rule details 

## Day-5:-

### Azure Log Analytics:-
* A log analytics workspace is used for storing all of your monitoring data.
* Each log analytics workspace has its own data repository and configuration.
* You can configure different data source to send their data onto the log analytics workspace. 
* These source includes:-
  - Azure Virtual machine
  - Hybrid windows 
  - Linux Machine
  - Azure resource that are part of your subscription

* Basically it install Log Analytics Agent.

## Day-6:-

### Azure log Analytice-Queries:-
* In this we have to understand how to work with Azure Log Analytics Queries.

### Azure log Analytics-Managing Access:-
* We can configure access to our log analytices workspace with the help of **Role-Based Access Control**.
* **There are 2 in-built user for log analytices workspace**:-
  1. **Log Analytics Reader**:-
     * With this role, a user can view and search all monitoring data.
     * The user can also view monitoring settings. This includes viewing the configuration of Azure diagnostic and all Azure resources.

  2. **Log Analytics Contributor**:-
     * This has all the privileges of the Log Analytics Reader.
     * Here the user can also create and configure Automation accounts.
     * The user can also add remove management solutions
     * The user can also configure the collection of logs from Azure storage and edit the monitoring settings from Azure resource. 

## Day-7:-

### Azure Diagnostic-Virtual Machine:-
* In this we have to cover about Diagnostic feature which is available for Azure Virtual machine.
* Also we have to cover how to work with the diagnostic feature.
* **What is diagnostic feature which is available for Azure Virtual Machine:-**
  * This is a feature that allow us to collect monitoring data from the guest from the guest operating system for Azure compute resources.
  * For collection of information, Azure will install the **Azure Diagnostic Extension** on your Azure Virtual Machine.
  * There are different type of data that can be collected:-
    * Windows Event Logs
    * Performance counters
    * IIS Logs(Usages information for the IIS websites that are running on the guest OS)
    * Application Logs
    * Crash dumps(Information about state of process if application crashes)
    * File based logs(These are logs that are created by the application or services)
    * Agent diagnostics logs(Information about Azure diagnostics agent)

### Creating a resource-Azure Web Apps:-
* Here we have to create Azure Web Apps
* We have to publish a solution onto the Azure Web App

## Day-8:-

### Application Insights:-
* **What we have to learn:-**
  * Overview of Application Insights
  * Using Application Insights

* **Overview of Application Insight:-**
  * This is an **Application Performance Manageemnt Service** for developers and DevOps proffesionals
  * With this service we can monitor our live applicaions
  * It helps to automatically detects performace issues and also help in diagnosing issues
  * Here we can get request rates, response times and falure rates for our pages
  * We can get page views and load performance as they are reported by the users' browser
  * It works with variety of platforms includes .Net, Node.js, java and python

### Monitoring Azure resources:-

* **What are we going to learn**
  * Using the datadog system for monitoring

* **What is datadog**
  * Datadog is a monitoring service for cloud-scale applications, providing monitoring of servers, databases, tools, and services, through a SaaS-based data analytics platform

## Day-9:-

### Visual Sutdio App Center:-
* **What we have to cover:-**
  * What is Visual Studio App Center
  * What goes into device registration

* What is Visual Studio App Center?
  * This service is used to **automate and manage** the lifecycle of IOS, Android, Windows and MacOS application
  * We can connect to our repo and automate our builds
  * We can then test the builds on real devices in the cloud
  * We can distribute apps to beta testers
  * We can also monitor real-world usages with crash and analytics data

* **Distribution Groups:-**
  * These are used to control access to release
  * Here the distribution group is a set of users
  * We can release the application to the users via distribution groups
  * **Private Distribution Group:-** Here users are invited by email. The users can then login into Visual Studio App Center and then test the application.
  * **Public Distribution Group:-** This is for unauthorized users. Here user can download the application via a link
  * **Shared Distribution Group:-** These are groups that are shared across multiple applications in a single organization.

## Day-10:-

### Azure Monitor-Dynamic thresholds:-
* **What are we have to cover:-**
  * What are Dynamic thresholds in Azure Monitor
  * Quick look at dynamic thresholds

* **What are Dynamic thresholds in Azure Monitor:-**
  * We can create alerts in Azure Monitor based on dynamic thresholds
  * Here Azure Monitor uses its internal *machine learning algorithms* to identify patterns and anomalies based on historical metrices collected by Azure monitor resources
  * When we define alerts an alerts based on a matric, you can choose a setting known as *sensitivity*
  * This defines what is the amount of deviation from metric behaviour that would be use to generate alerts.
  * **There are three levels of sensetivity:-**
    * **High:-** Here an alerts would be generated even on the smallest deviation. This results in more alerts being generated
    * **Medium:-** Here alerts would be based on more balanced thresholds. Here fewer alerts would be generated
    * **Low:-** Here only if there are major deviations, then alerts would be generated. This would results in fewer alerts. 

  * For new resources, dynamic thresholds won't be triggered three days on unless 30 samples of metric data is made available.
  * We can also define advanced settings of dynamic alerts
  * This allow us to create alerts based on the number of deviation 

# Section-2: Devlop a Site Reliability Engineering Strategy:-

## Day-11:-

### What is Site Reliability Engineering:-
* **What are we going to learn:-**
  * What is Site Reliability Engineering.
  * How can you increase the reliability of system with the help of Azure services.

* **What is Site Reliability Engineering:-**
  * This is an engineering discipline that is used to help an organization achieve an appropriate level of reliability in their systems, services and products.
  * Sometimes it is not necessary for a system to be 100% reliable. This is also difficult to achieve
  * In crucial sectors like aviation or medical you would strive for high reliability
  * To achieve high reliability, you would need to invest more.
  * Hence always set a goal with relevant stakeholders on the ideal measure for reliability

* **How can we increase the reliability of system with the help of Azure services:-**
  1. Using Virtual Machine Scale sets:-
     * This is a service that allows you to spin up an identical set of virtual machines
     * Here the service can scale in and out based on demand.
     * It can increase the number of virtual machines running as part of your system if the load increases
     * It can also decrease the number of virtual machines running as part of your system if the load decreases 
  2. Using an Azure Load balancer:-
     * The Azure load balancer can be used to route requests to backend virtual machines
     * This helps to distribute traffic in an efficient way
     * It can also help ensure that your system still processes requests if one of your virtual machines goes down
  3. Using the Azure Traffic Manager Service:-
     * This is a DNS routing service
     * Here you can route traffic based on different routing methods
     * You have the priority routing that can be  used to route traffic to a secondary end point if the primary endpoints fails.


## Day-12:-

### Using Dashboard is Azure Monitor:-
* What we have to learn:-
  * How to work with dashboards in Azure

### Using Resource Graph Explorer:-
* **What we have to learn:-**
  * What is the Resource Graph Explorer
  * How to use the Resource Graph Explorer

* **What is the Resource Graph Explorers:-**
  * This is a service that allow you to browse for the resource that are part of your sebscription.
  * Here you can use queries based on the **kusto Query Language** to search for resources
  * The Resource Graph Explorer provides an enterface that helps in executing multiple queries, evaluating the results and viewing the results in the form of charts.  

## Day-13:-

### The Azure Load Balancer Service:-
* **What we have to learn:-**
  * What is the purpose of Azure Load Balancer
  * What is the Azure Load Balancer
  * What are the different components of the Azure Load Balancer
  * The different Azure Load Balancer SKU's 
  * Public and Internal Load Balancer

* **What is the Azure Load Balancer:-**
  * The Azure Load Balancer is used to distribute incoming traffic to backend virtual Machine
  * The Azure Load Balancer operate at **Layer-4** of the OSI(Open System Interconnection) model
  * This service can be used to provide higher availability for your application architecture

* **What are different components of the Azure Load Balancer**
  1. **Frontend IP Configuration:-**
     * This is the IP address assigned to the load balancer
     * If you have to load balance requests from the internet, then you can assign a Public IP address.
     * If you need to load balancer requests from the virtual network, then you assign a private IP address
  
  2. **Backend Pool:-** This is the group of virtual machines or instances in the virtual machine scale set that can be used to serve the incoming user requests.

  3. **Health probe:-** This is used to determines the health of the underlying instance in the backend pool.

  4. **Load-Balancing rules:-** This tells the load balancer what to do with the incoming traffic.

## Day-14:-

* **The different Azure Load balancer SKU's:-**
  1. **Basic Load Balancer:-**
     * This can support up to 300 instance in the backend pool
     * The backend pool can contain VMs that are part of an availability set or scale set
     * The health probes can be only TCP and HTTP
     * There is no SLA
  2. **Standard Load Balancer**
     * This can support upto 1000 instance in the backend pool.
     * The backend pool contain any virtual machine or virtual machine scale sets in a virtual network
     * The health probes can be only TCP, HTTp and HTTPS
     * You get an SLA of 99.99%

### Lab-using the Azure Load balancer:-
* We have to make network interface static
* We have to configure backend pool, Health probes, and load balancing rules.

### Virtual Machine Scale Sets
* **What we have to learn:-**
  * What is virtual machine scale sets
  * How to work with virtual machine scale sets
* **What are Virtual Machine Scale Sets:-**
  * This service allows you to create and manage group of identical and load balanced virtual machines
  * Here the number of underlying instances in the scale set can increase or decrease based on demand or based on a set schedule
    

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
  * Using virtual machine scale sets, you can add more scalability and availability for your application
  * **Scale Out:-** Increasing no of VM in scale set
  * **Scale In:-** Decreasing no of VM in scale set
  * Install the tool stress to increase the load on VM by using command
    - sudo apt-get install stress
  * To stress cpu use the below command
    - sudo stress--cpu 100

## Day-15:-

### Using Queues for scaling:-
* **What are we going to learn:-**
  * The concept of using queues for scaling
  * How to use queues in the scalling process
* The concept of using queues for scaling:-
  * Each time when there is request for workload to execute, the Web Application sends a message to Azure Queue Storage and based on number of message on queue the number of VM will get created.
* Using queues for the scaling process:-
  * We will create an Azure storage queue
  * We will create a scaling condition in an Azure Virtual Machine Scale Set based on Azure storage queue 

## Day-16:-

### Usage of Azure Trafic Manager:-
* **What we have to learn:-**
  * What is the Azure Traffic Manager Service
  * What are the different routing methods vailable
  * How to use service itself 
* What is the Azure Traffic manager service:-
  * The Azure Traffic Manager service is a DNS-based traffic load balancer
  * This service helps you to distribute traffic to services across global Azure regions
  * The Traffic manager service directs client requests to the most appropriate service endpoint based on the traffic-routing method and base on the health on the of the endpoints
  * An endpoint is reffered to an internet facing service that is hosted inside or outside of Azure
* What are the different routing methods available:-
  1. **Priority:-** This is used to direct traffic to a secondary endpoint if the primary endpoint fails
  2. **Weighted:-** This can be used distribute traffic across a set of endpoints
  3. **performance:-** This routing mathod can be used to direct users to the closest endpoint when it comes to lowest network latency
  4. **Geographic:-** Here user are directed to specific endpoints based on the geographic location of the DNS query
  5. **Multivalue:-** Here multiple healthy endpoints are returned to the client
  6. **Subnet:-** Here a set of end user IP address ranges are mapped to specific endpoint

## Day-17:-

### Understanding your SLA
* **What are we going to learn:-**
  * Common SLA provided for Azure Services
  * Understanding of composite SLA
* Common SLA provided for Azure Services:-
  * Azure normally gives an Service Level Agreement of 99.9% for all paid services
  * If you have Virtual Machine that have two are more instances that are deployed across two or more Availability Zones in the same Azure region, you will guaranteed Virtual Machine connectivity to at least one instances that are deployed across an availability set, you will be guaranteed Virtual Machine connectivity to atleast one instance at 99.95% of the time.
  * For an Azure Standard Load Balancer that serves two or more healthy Virtual Machines instances, you will be guaranted availability 99.99% of the time
  * You won't get the same SLA for the basic Load Balancer
  * For Azure Storage accounts, you get a general SLA of 99.9% for the read and write operations
* **Understanding Composite SLA:-**
  * When you have multiple services for your application, you have to consider the SLA for each services
  * Let's say that you have an application that that makes use of the Azure Web App service and the Azure SQL Database service
  * For Azure Web Apps, you get an SLA of 99.95%
  * For Azure SQL Database, you get an SLA of 99.99%
  * Hence the composite SLA for the system would be 99.95% * 99.99% = 99.94%

## Day-18:-

### Recovery Strategies:-
* **What we have to learn:-**
  * Planning for Disaster Recovery
  * Quick look at geo-replication for an Azure SQL database
* Planning for Disaster Recovery:-
  * When you host application using cloud infrastructure, you always have to plan for disaster recovery scenarios
  * This is important for application that are cretical and need to be up and running all the time
  * Businesses will normally have procedures in place for recovery for their application
  * The procedure would be dependent on many aspects such as the importance of having a recovery solution and the cost
  * Also aspect such how long can the application can be down and what is the acceptable loss of data
  * we have to set the system for ongoing replication of data
  * **Cost is important** Here you need to pay for the duplicate infrastructure in the East US region
  * **Why we would choose on-going replication?** This would ensure we don't loose that much data in the event of a disaster

# Section-3: Develop a Security and Compliance Plan:-

## Day-19:-
### Quick review on Azure AD:-
* **What we have to learn:-**
  * What is Azure Active Directory
  * How does it work
  * Pricing options

* What is Azure Active Directory:-
  * This is a cloud-based identity and access management service
  * We can create users and groups in Azure AD
  * We can assign licences to users
  * We can give access to resource in Azure to users defined in Azure AD
  * You can also grant different roles to users in Azure AD

* How does it work:-
  * When we need to access resources in Azure we first need to sign in to our Azure AD and then based on the permession that we haave we can able to access the resources

* Pricing Options:-
  * **Azure Active Free:-** This provides user and group management. It also provides on-premises directory synchronization, basic reports and self-service password change for cloud users
  * **Azure Active Directory Premium P1:-** Here hybrid users can acccess both on-premises and cloud resources. It also support the user of dynamic groups, cloud write-back capabilities and self-service password reset for on-premises users
  * **Azure Active Directory Premium P2:-** This provides important features such as Azure Active Directory Identity Protection and Privileged Identity Mangement

## Day-20:-

### Managing your Azure AD user and group:-
* **What we have to learn:-**
  * Users and groups
* Users and groups:-
  * We can create users in Azure AD
  * We can also able to logically group the users into groups
  * We can assign Azure AD roles to either users or groups
  * We can also assign permissions to resources in our Azure subscripyions to users or groups

### Multi-Factor Authentication
* **What we have to learn:-**
  * What is Multi-Factor Authentication
  * How to enable Multi-Factor Authentication
* What is Multi-Factor Authentication
  * This is the process where in the user is prompted for an additional form identification during the sign-in process
  * This makes the sign-in process more secure
  * The following methods are available form of MFA
    1. Microsoft Authentication App
    2. SMS
    3. Voice Call
    4. Hardware token

## Day-21:-

### Conditional Access Policies:-
* **What we have to learn:-**
  * What are conditional access policies
  * How to work with coditional access policies
* What are conditional access policies:-
  * Conditioanal access policies are used to allow users to access a resource only if they perform a certain action
  * It is used to add an extra layer of security when it comes to accessing application such as Azure Portal
  * You can  provide access to users based on signals available and creating conditioan access policies
* Common Signals:-
  * **User or group membership:-** Only apply policies to certain users and groups
  * **IP Location Information:-** Here companies can create configure IP address to block or allow traffic from
  * **Device:-** Here only users using devices with specific platforms could be allowd to access
  * **Real time and calculated risk detection:-** Here Azure AD Identity Protection can be used to identify the sign-in risk behaviour. The policy can then be used to either grant or block access based on the risk sevierity 

### Azure AD Privileged Identity Management:-
* **What we have to learn:-**
  * What is the Azure AD Privileged Identity Management
* What is Azure AD Privileged Identity Management:-

  * We can use this to provide just-in-time privileged access to Azure AD and Azure resources
  * We can assign time-based access to resources using start and end time using start and end dates
  * We can ensure approval is taken before the activation of privileged roles
  * We can also ensure multi-factor authentication is carried out to activate any role
  * Get notification when privileged roles are activated 
  * We need to ensure each user that needs to use Azure AD Privileged Identity management is assigned an Azure AD Premium P2 license
  * To start using Azure AD Privileged Identity management, first ensure to login as the Global Administrator 
  * Go to the Azure AD Privileged Identity Mangement service
  * Consent to using Privileged Identity Mangement
  * We will then be requested to carry out multifactor authentication

## Day-22:-

### Azure Key Vault:-
* **What we have to learn:-**
  * What is the Azure key vault service
  * Working with the Azure key vault service
* What is the Azure key vault service:-
  * This is a tool that can be used to securely store and access secrets
  * Secrets can be API keys, password or certificates
  * **Example:-** 
    * Let's say an application is being developed that is used to encrpt data. The data needs to be encrypted using an encryption key
    * The encryption key, instead of being stored in the application itself, can be stored in the Azure key vault service
    * The application can then make a secure call to get the encryption key from the Azure key vault service
  * You can also set access permission to service principals for the secrets, keys and certificates stored in the Azure key vault
  * There are different permissions available for working with secrets, keys, or certificates
  * You can also protect your key vault and its objects using the soft-delete feature
  * Here event though the key vault or an object is deleted, the object would still be available for a duration of time
  * The retention period can be configured for 7 to 90 days

### Service Principal:-
* **What we have to learn:-**
  * What is a security principal
  * How to use a security principal
* What is a security pricipal:-
  * In order to access resource that are secured by an Azure AD tenant, the access must be represented by a security pricipal
  * The security pricipal defines the access policy and the permissions for the user or the application in the Azure AD tenant

## Day-23:-

### Azure Active Directory:-
* **What we have to learn:-**
  * Using a managed identity
* Using a Managed Identity:-
  * A common challenge for developers is the management of secrets and credentials to secure communication between different services. On Azure, managed identities eliminate the need for developers having to manage credentials by providing an identity for the Azure resource in Azure AD and using it to obtain Azure Active Directory (Azure AD) tokens. This also helps accessing Azure Key Vault where developers can store credentials in a secure manner. Managed identities for Azure resources solves this problem by providing Azure services with an automatically managed identity in Azure AD.

### Azure Security Center:-
* **What we have learn:-**
  * What is Azure Security Center
  * A look at Azure Security Center
* **What is Azure Security Center:-**
  * This is a security system that is available in Azure
  * It provides **advanced threat protection** for our application in the cloud or in  our on-premise infrastructure
  * Azure Security Center has the ability to access your environment and gives you the the uderstanding on wheater your resources are secure or not
  * **There are two pricing tiers for azure security- free and standard:-**
    * Free:- Missing OS patches assessment, Security Misconfiguration assessment, Endpoint protection assessment, Disk encryption assessment.
    * Standard:- Virtual Machine Behavioural Analytics, Network-based security alerts, Just-In-Tine VM access, Adoptive application controls.

### Azure Policies:-
* **What we have to learn:-**
  * What is the Azure Policy service
  * How to use the  Azure policy service
* What is the Azure Policy Service:-
  * This is a service that can be used to create, assign and manage policies
  * These policies can be  used to enforce rules that resources must abide by
  * Policies can also show non-compliance of existing resources
  * There are already many inbuild policies in place 
  * Defination contain all inbuild policies 

# Section-4:-Manage Source Control:-

## Day-24:-

### Using Source Control:-
* **What are we going to learn:-**
  * Using a versioning control system
  * Centralized Version Control System
  * Distributed Version Control System
  * Benefits of each version control system
* **Using a versioning control system:-**
  * Developers can use a versioning control system to record changes that are made to their source code file over time
  * This gives the developer the ability to revert back to a previous file version or even back to a previous project version
  * The source code versioning system also has the ability to compare changes made to a file from one version to another
  * The most popular source code system is git 
* **Using a centralized source control system:-**
  * It's beneficial to use when you have a large code base 
  * Here you can specify fine grain permission at the file level
  * You can monitor the usages of files because the check-in and check-out happens at the server level
  * You can also lock files if required. This would prevent these files from being changed on server 
  * Eg:- Team Foundatiot
* **Using a distributed source control system:-**
  * You are giving the developer full control over the repository by allowing to use a local copy
  * The developer also gets the full history along with the repository code
  * It's great to use when you have many distributed teams
  * Great when working with open source code bases
  * Eg:- git

### Azure Repos- Team Foundation Version Control
* **What we have to learn:-**
  * How to work with Team Foundation Version Control

### Azure Repos-Git:-
* **What we have to learn:-**                                           
  * Working with Git locally                                                   
  * Working with Git in Azure Repos                                            
* |Create a file Locally|--> |Initialize an empty git repository|--> |Add the files that need to be commited|--> |Commit the file locally|--> |Push the changes to Azure Repos|                             
                                                                                  
## Day-25:-

### Azure Repos- Git Branches:-
* **What we have to learn:-**
  * What are branch in Git
  * How to work with branches in Git
* What are Branches in Git:-
  * Branches help developer to work on a different line of development and not touch the main branch of work
  * So let's say that developers want to work on a new feature of an application 
  * Instead of adding the code changes to the main branch, they can create a new branch and add the code to the new branch
  * The git branches are very light weight and hence easy to use
  * Use 'git branch branch_name' command to create a new branch
  * Use 'git checkout branch_name' to make changes on new branch not the master
  * To check on which branch pointer is pointing use git branch command 

## Day-26:-

### Azure Repos - Pull requests:-
* **What we have to learn:-**
  * What are pull requests in Git
  * The different types of merges
  * How to work with Pull requests in Git
* What are pull requests in Git:-
  * Let's say a developer has gone ahead and made chages to a particular branch in their local repository, and now the developer wants to merge the changes onto the branch into Azure Repos
  * Let's say that the company want to insure that the changes are viewed before they can be finally merged onto the repository in Azure repos
  * For this there can be restriction placed on the branch where in the developer first needs to intitiate a pull request
  * The pull request can be reviewed by a lead developer 
  * The lead developer can check what are the chages that are going to be made
  * If the change are approved, the pull request can be approved
  * You can protect your branches with the help of branch policies
* The different type of merges:-
  * **Merge(no fast-forward):-** Here all the individual commits in the pull requests branch are preserved as-it-is. A new merge commit is created which unites the master branch and the pull request branch
  * **Squah commit:-** Here the resulting commit is not exactly a merge commit, Here it just maintains a simple, straight, linear history
  * **Rebase:-** Here the Rebase will take each individual commit in the pull request and cherry-pick them into the master branch
* Use 'git merge branch_name' to merge it in master branch
* Then do 'git commit'

### Visual Studio - Azure Repos-Git:-
* **What we have to learn:-**
  * Using Visual Studio to publish a project onto Azure Repos-Git

## Day-27:-

### Code Reviews:-
* **What we have to cover:-**
  * Using Code Review
* Using Code Rewiews:-
  * Performing reviews of an application code base is important
  * You can perform peer review
  * Here you can request for reviews from your peers and reviewed the change requests accoudingly
  * You can also use automated software to conduct code reviews 

### GitHub Code Scanning:-
* **What we have to learn:-**
  * Understanding code scanning in GitHub
* Understanding code scanning in GitHub:-
  * Code scanning is a feature that is available in GitHub
  * This can be used to find for security vulnerabilities and coding errors in your source code
  * GitHub can be then generated alerts based on the vulnerabilities encountered 
  * Code scanning can be used with CodeQL
  * This is a semantic code analysis engine that treats code as data
  * It can then find for potential vulneraabilities in the code 

# Sction-5:-Facilitate communication and colleborotion:-

## Day-28:-

### Starting with Azure DevOps services:-
* **What are we going to learn:-**
  * What is available with Azure DevOps
  * What is an Azure DevOps project
  * The pricing involved with Azure DevOps
* What is available with Azure DevOps:-
  * **Azure Boards:-** Here teams can create and track user stories, backlog items, track, feature and bugs that are linked onto a project
  * **Azure Repos:-** This is a set of version control tools that helps you to manage your code.
  * **Azure Pipelines:-** This can be used to automatically build and test your code projects
  * **Azure Test Plans:-** Here you can manage manual testing which include user acceptance testing, Exploratory testing and Shareholder feedback
  * **Azure Artifacts:-** Here you can create and shared Maven, npm, and Nuget package feeds from public sources with teams of any size
* What is an Azure DevOps projects:-
  * An Azure DevOps projects is an encapulation of the repository for source code and also for the group of people who would be responsibe for planning, tracking and collaboration on the software solution being build
  * If you have different business units, you can add projects for each business unit

## Day-29:-

### What are Azure Boards:-
* **What we have to learn:-**
  * What are Azure Boards
  * The basic process
  * The Agile process
  * The Scrum process
  * The CMMI process
* What are Azure Borads:-
  * This is a service that helps teams to manage their software projects
  * It has support for Scrum and kanban
  * Here you can quickly create and track user stories, backlog items, feature and bugs that are associated with a project 
* The Basic Process:-
  * Choose this process when the team needs the simplest model to work with in Azure Boards
  * **Steps:** Epic-> Issue-> Task
  * **The basic Process-Workflow(Bi Directional):** To Do-> Doing-> Done
* The Agile Process:-
  * Choose this process when when the team need to use Agile process auch as Scrum
  * Here the team would want to track user stories and track development and test activities
  * Can also track bugs on the kanban boards
  * **Steps:** Epic-> Feature-> User stories-> Task Bug-> Task  | issue
  * **The Agile Process-Workflow(Bi-Directional):** New-> Active-> Resolved-> Closed | Removed
* The Scrum Process:-
  * When you specifically want to align with the scrum process
  * Here you track the product backlog and the bugs on a kanban board
  * **Steps:** Epic-> Feature-> Product backlog item-> Task  | Bug-> Task  | Impediment(issue and bug tracking)
  * **The Scrum Process-Workflow(Bi-directional):** New-> Approved-> Committed-> Done | Removed
* The CMMI Process:-
  * When the company follow a more formal project process
  * **Steps:** Epic-> Feature-> Requirement-> Task | Bug-> Task | Change Request | Issue | Review | Risk
  * **The CMMI Process-Workflow:** New-> Active-> Resolved-> Closed

### Working with Azure Boards:-
* **What are we going to learn:-**
  * How to work with Azure Boards

### Azure Boards- Team users:-
* **What are we going to learn:-**
  * How to add a user to the organization and then to the team

## Day-30:-

### Revision Day-1:-
* Revised complete **Introduction to DevOps Section**
* Revised Complete **Devlop an Instrumental Strategy Section**

## Day-31:-

### Revision Day-2:-
* Solved questions on Devlop an Instrumental Strategy Section
* Revised Complete **Develop a Site Reliability Engineering Section**
* Revised Complete **Develop a security and compliance plan Section**
* Revised Complete **Manage Source Control Section**
* Revised Complete **Facilitate Communication and Collaboration Section**

## Day-32:-

## Revision Day-3:-
* Solved questions on Manage Source Control Section
* Solved questions Facilitate Communication and Collaboration Section

## Day-33:-

### Lab-Azure Boards-Charts:-
* **What are we going to learn:-**
  * What are the key concepts with dashboards
  * The different chart available
  * How to create a sample chart and add it to a dashboards

* What are the key concept with dashboards:-
  * These are customized and interactive signboards that helps to provide real-time information.
  * The dashboards are linked with a team or a project
  * The dashboards can be used to deploy charts and widgets
  * **Charts:-** These are trend charts that can be created with a work item query
  * **Widgets:-** This helps to display configurable and charts on dashboards

* The different charts available:-
  * **Burndown and Burnup:-** The Burndown chart focuses on the remaining work within a specific period of time. The Burnup chart focuses on the complete work. Both of the chart type can be used to see if the team is on the track to complete the set of work by the end date.
  * **Cycle time:-** This is used to look at the time taken to close a work item after work on it has started
  * **Load time:-** This defines the time taken to close a work item after it has been created.  

### Azure Boards - Slack:-
* **What we have to cover:-**
  * Intergration of Azure Boards with Slack

* Intergration of Azure Boards with Slack:-
  * You can use the Azure Boards application for slack to create work item and monitor the work item activity in the Azure Boards projects from a slack channel
  * You have first add the Azure Boards app to the slack workspace
  * Then link the Azure Boards project to the Azure Boards app in the slack
  * Setup subscription for the work related events in the slack channel 

# Section-6:- Define and Implement continious Integration-Build Automation:-

## Day-34:-

### What is Continious Integration:-
* **What we have to learn:-**
  * What is Continious Integration
  * The need for continious integration
  * Tools for continious integration

* What is Continious Integration:-
  * Used to complement the entire DevOps process
  * provides automation for your entire applicationn lifecycle
  * Allows to detect issues and bugs early on in your development lifecycle.

* Tools for continious integration:-
  * The right tools are important
  * continious integration tools:- Jenkins, Atlassian Bamboo, Teamcity
  * You would also implement your source code versioning tool such as Git and GitHub
  * You would also implement your testing tools with the continious integration tools
  * Azure DevOps service service has Azure Pipeline

## Day-35:-

### What is Azure Pipeline
* **What we have to cover**
  * What are Azure pipelines
  * The different parts of Azure pipeline








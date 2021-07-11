# **Target- To prepare and clear Technologies for Microsoft Azure Architects (AZ-303) Certification Exam**

## **Demo Labs**
1. [**Demo: Creating a Web App from AzureCommand Line Interface**](https://github.com/sauravraghuvanshi/100-Days-of-Azure/blob/main/Microsoft_Certified_Solution_Architect_Expert/Labs/Demo-Creating%20a%20Web%20App%20from%20Azure%20Command%20Line%20Interface.pdf)
2. [**DEMO: Deploying and Connecting to a Windows Virtual Machine via the Azure**](https://github.com/sauravraghuvanshi/100-Days-of-Azure/blob/main/Microsoft_Certified_Solution_Architect_Expert/Labs/DEMO-%20Deploying%20and%20Connecting%20to%20a%20Windows%20Virtual%20Machine%20via%20the%20Azure.pdf)
3. [**DEMO: Deploying and Connecting to a Linux Virtual machine via the Azure Portal**](https://github.com/sauravraghuvanshi/100-Days-of-Azure/blob/main/Microsoft_Certified_Solution_Architect_Expert/Labs/DEMO-Deploying%20and%20Connecting%20to%20a%20Linux%20Virtual%20machine%20via%20the%20Azure%20Portal.pdf)
4. [**Demo: Create an Availability Set**](https://github.com/sauravraghuvanshi/100-Days-of-Azure/blob/main/Microsoft_Certified_Solution_Architect_Expert/Labs/Demo-Create%20an%20Availability%20Set.pdf)
5. [**DEMO: Implementing a VM Scale Set with Autoscaling**](https://github.com/sauravraghuvanshi/100-Days-of-Azure/blob/main/Microsoft_Certified_Solution_Architect_Expert/Labs/DEMO-%20Implementing%20a%20VM%20Scale%20Set%20with%20Autoscaling.pdf)
6. [**DEMO: Deploying Software with VM Extensions**](https://github.com/sauravraghuvanshi/100-Days-of-Azure/blob/main/Microsoft_Certified_Solution_Architect_Expert/Labs/DEMO-Deploying%20Software%20with%20VM%20Extensions.pdf)
7. [**Demo: Deploying IIS with Custom Script Extension**](https://github.com/sauravraghuvanshi/100-Days-of-Azure/blob/main/Microsoft_Certified_Solution_Architect_Expert/Labs/DEMO-Deploying%20Software%20with%20VM%20Extensions.pdf)




## **Day-37:-**

### **Description:-** 
* This learning path is designed to help prepare for the AZ-303 Microsoft Azure Architect Technologies exam and at the same time make ready for Azure Architect Role. 

* The AZ-303 and AZ-304 exams replace the older AZ-300 and AZ-301 exams, which will retire on September 30, 2020. These two exams are part of Microsoft’s role-based certification program. Candidates who pass both exams will earn the Microsoft Certified: Azure Solutions Architect Expert certification.

* The AZ-303 exam tests your knowledge of four subject areas and that’s how we’ve structured this learning path as well. We’ll start with implementing and monitoring Azure infrastructure. This is the biggest section, and it covers a wide variety of topics, including storage, virtual machines, networking, Azure Active Directory, and more. Next, we’ll show you how to implement management and security solutions. After that, you’ll learn how to create and deploy apps using either Azure App Service or one of the container services, such as Azure Kubernetes Service. Finally, we’ll cover how to implement and manage data platforms.

### **Learning Objectives**
* Implement and monitor an Azure infrastructure
* Implement management and security solutions
* Implement solutions for apps
* Implement and manage data platforms

### **Intended Audience**
* People who want to become Azure cloud architects
* People preparing for Microsoft’s AZ-303 exam

# **Module: Overview of Azure Services**

## It is really great place to start the prepration by knowing what all services Azure provied in different domain, so that when we start to design architecture for an application at that time we know what all options and alternatives we have for each services

## **Day-38:-**

### **Azure Overview:-**
**For any core application we need 3 core services i.e Compute, Storage, and Networkng**
* **Compute:-**
  1. Azure Virtual Machine:-
     * Infrastructure as a Service Compute Option
     * Best for lift and shift

  2. Azure App Service:-
     * PaaS Solution
     * This platform let you host web and mobile application without even thinking about the underline infrastructure
     * For most applicatiuon Azure App Service is better option then Azure VM but there are situation like if our application is neither web or mobile app then we can't able to use App Service

  3. Azure Container Instances:-
     * These are self contained software environment
     * It contain complete application plus all the third-party package it needs

  4. Azure kebernetes Service:-
     * Best for compex application that contain multiple containers

  5. Azure Functions:-
     * It is the Serverless Compute Offering
     * It contain single function rather then compete application
     * It has consumption plan: Only use resource when a function is running 

## **Day-39:-**

### **Azure Overview:-**
* **Storage:-**
There are even more storage option then for copmute. That's beacuse I included database and other data store in the same category.
  1. **Azure Blob Storage:-**
     * It is simplest storage form
     * It is also called object storage
     * It is just a collection of files
     * It doesn't have hierarchical folder structure. It basically have the flat structure.
     * It is mainly used for unstructured data e.g images, videos, log etc.
     * It has multiple access tier:-
       - **Hot Tier:-** Preffered for frequently accessed data
       - **Cool Tier:-** Infrequently accessed
       - **Archive:-** Rarely Accessed
  2. **Hierarchical file storage:-**
     * 1. **Azure File Storage:-**
          * Serves up file share that you can mount on window servers.
     * 2. **Azure Data Lake Storage Gen 2:-**
          * Hadoop-compatible storage for use with data application.
  3. **Relational Database:-**
     * 1. **Azure SQL Database:-**
     * 2. **Open Source:-** 
          * Azure Database for MySQL
          * Azure Database for MarioDB
          * Azure Database for PostgreSQL
  4. **Azure Synapse Analytics:-**
     * It is a data warehouse solution
  5. **NoSQL Database:-**
     * Sutable for application which have large
          



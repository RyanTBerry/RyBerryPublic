# Developer and Insight Days
## App Modernization Hack Event

### Overview
This hack is intended to be delivered over the course of a single day that walks through how one can migrate on-premises workloads using the 4-"R" options:
* Rehost
* Refactor
* Rearchitect
* Rebuild

The hack focuses on 3 common methods -- rehost, refactor and rearchitect using a 2-tier ASP.NET webform line-of-business (LOB) application connected to a SQL database. There is a small-amount of content available in the delivery slides to walk through the idea behind these migration paths as well as a primer on Azure PaaS capabilities and Containers.

Option: To save time; the instructor could pre-migrate the IaaS SQL database to Azure SQL DB and provide the connection string to the class to ensure the course material is able to be completed during the day 

### Resources
* [ARM Templates to build jump-box with Visual Studio for Lab](https://github.com/007FFFLearning/ADS-Containers/tree/master/Sources)
* [Self-Contained Web Application](./Application)
* [Azure Migration Documentation](https://docs.microsoft.com/en-us/azure/migrate/contoso-migration-overview)

### Suggested Schedule
There is a fair amount of content to cover in a short period of time; the container session maybe challenging to complete but the attendees will be left with the material and guidance on how to complete once they leave.  

| Time          | Topic
| ------------- |:---------------------------------------------------------------
| 09:00–09:30   | Registration
| 09:30-10:30   | Migration Strategies:  Approaches to migration – VMs and PaaS
| 10:00-12:00   | [Workshop 1: Migrating to VMs on Azure](./Labs/Lab1.pdf)
| 12:00-12:30   | Lunch
| 12:30-13:00   | PaaS + Serverless options overview
| 13:00-14:00   | [Workshop 1a: Migrate VM Hosted Database to SQL Azure DB](./Labs/Lab1a-Optional.pdf)
| 13:00-14:00   | [Workshop 2: Migrating to Azure PaaS](./Labs/Lab2.pdf)
| 14:00-14:15   | Break
| 14:15-15:15   | Cloud Native: Moving to Containers
| 15:15-17:00   | [Workshop 3: Migrating to AKS](./Labs/Lab3.pdf)

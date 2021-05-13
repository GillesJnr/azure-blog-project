# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*


**Answer ****

# Analysis for Cost
Virtual Machines has lower upfront costs considering no hardware is purchased or maintained when compared to hosting the application on premise. Vm's have different prices depending on the specifications needed. The least specification with a linux operating system with 1 cores, 0.75 gb ram, 20 gb temporary storage of a vm costs $0.018/hour and approximately $13.19 a month.But aside this will be time cost needed to be able to configure and maintain the Operating system, Application and security of the application. 

App Services also have different pricing based on the chosen app service plan. App Services also have flexible pricing due to the ability to scale the application vertically and horizontally thus either increasing the size of memory or increasing the size of ram. The least specification with a linux operating system with 1 core, 1.75 GB RAM, 10 GB Storage costs $0.018/hour and approximately $13.14 per month. Which to a developer is cost effective when the application doesn't need much RAM and processors.

Note: Pricing details obtained using https://azure.microsoft.com/en-us/pricing/calculator/

# Analysis for Scalability
Both the Virtual Machine and App Service can be scaled vertically and horizontally. Virtual machines are scaled using Virtual Machine Scale Sets and Load Balancers whiles App Service is scaled using 








### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

**Answer**
There will be a need for my app to change from using Azure App Service to Azure Virtual Machines when there will be softwares needed to be used for or by my application and would need to be manually installed. This will then inform the need to change because App Services limits access to the host server. 

Also, When the current plan limits my application, Thus, Azure App Services provides a maximum of 14 Gigabyte Memory allocation and a maximum of 4 vCPU's. If my application tends to exhaust these capacities and would need additional memory and cpu's, I will have to go with a Virtual Machine. 
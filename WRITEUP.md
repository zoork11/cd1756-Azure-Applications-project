# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

Costs for running the CMS as an App Service are lower than using a VM. With the App Service effort for configuring an managing the environment the CMS is running in is much lower. Ansd also the prices for the App Serices are lower. But an App Service has more constraints in terms of scalability than a VM, since there are no requirements given regarding resources, this can be neglected. In terms of availability an App Service helps since Microsoft will take care of it and enusres that the app is available at 99,95%. If a VM is used we are responsible for the availability. The workflow for developing and hosting an app is less complex with an App Service, since Microsoft serves a fully configured system where only minimal configuration and no management of the system is needed.

For the article CMS application i would choose an App Service. My main reasons for using the App Service are the reduced complexity and the faster setup of a fully working system. Since the flexibility and scalability of a VM are not needed or demanded in this task an App Service is the better choice.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.*

If the resource requirements or the need for flexibility would change a VM can be considered. Since the resources are limited with App Services, this could force a change to a VM. If special requirements demand more control over the environment a VM is needed as well.
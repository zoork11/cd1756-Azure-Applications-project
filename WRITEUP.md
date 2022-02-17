# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

Costs for running the CMS as an App Service are lower than using a VM. For the same resources the price for running a VM is higher. For example the smallest plans for both are suitable for this CMS app. The App Service in that plan would be free, while the VM would cost $13.14.
Also with the App Service, effort for configuring an managing the environment of the CMS app is much lower. This also contributes to a lower price but increases the flexibility and control over the app.
An App Service has more constraints in terms of scalability than a VM, since there are no requirements given regarding resources, this can be neglected.
In terms of availability an App Service helps since Microsoft will take care of it and ensures that the app is available at 99,95%. If a VM is used we are responsible for the availability.
The workflow for developing and hosting an app is less complex with an App Service, since Microsoft serves a fully configured system where only minimal configuration and no management of the system is needed.

|                        | VM        | App Service
| ---------------------- | --------- | ------------- |
| Costs                  | higher    | lower         |
| Control/Flexibilty     | higher    | lower         |
| Management effort      | higher    | lower         |
| Scalability            | higher    | lower         |

The table shows the differneces between the two services. For the CMS app my priority would be to have lowest possible management effort in order to focus on creating the application instead of setting up the environment. It is faster to setup a fully working app due to the reduced complexity. Another nice benefit are the lower costs for running an App Service.
Since the flexibility and scalability of a VM are not needed or demanded in this task an App Service is in my opinion the better choice.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.*

If the resource requirements or the need for flexibility would change a VM can be considered. Since the resources are limited with App Services, this could force a change to a VM. If special requirements demand more control over the environment a VM is needed as well.
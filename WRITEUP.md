# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 


If this application is later implemented using another programming language that is not supported by Azure app service. here, I will choose VM and create the environment for that programming language.

Using App service, I have limited access to the host server, if I want to control the underlying OS or install a software on the server, I have to choose Virtual Machine.

For advanced scaling (auto) and traffic management features, I would go for VM. this can be done easier with Azure Virtual Machine Scale Sets.

Azure app service has a hardware limitations. Also is not an appropriate solution for apps which have scope to expand for future. Instead, VMs are preferred. If this app grows to a larger scale, when we have vast increase in the number of users or when more features are added to the app, I would choose a Virtual Machine.
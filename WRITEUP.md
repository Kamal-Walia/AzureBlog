# Write-up Template

## Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

## Why App Service over Virtual Machine? 
I choose to deploy using App Service because it is a PaaS so it is scalable.App Service also supports Python language and Github, which are the dependencies used for this project. It lets me focus on the app development and not to worry about the infrastructure services. Also it is cost efficient.

## Why Not Virtual Machine? 
I don't choose to deploy with Virtual Machine (VM) because it is a Infrastructure as a Service (IaaS). This project is a web applicaiton so I don't have to create and use virtual machine in the cloud. I don't need to access and control the VM, as well as other infrastructures such as memory, CPU, RAM, storage, etc. Furthermore, VMs are more expensive and more time consuming to develop for this project. 

## How the app and any other needs would have to change for you to change your decision to use Virtual Machine? 
I have to manually scale my app.
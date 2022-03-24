# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

Analyze:

|        	    | Virtual Machine       		   	       														| Web App Service                                                                     	  |
|---------------|-----------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|
| Cost			| The cheapest price to deploy an app into Virtual Machine is $0.0146/hour(Sku B1s)	    		| The cheapest price to deploy an app into App Service is $0.013/hour(Sku D1)             |
| Scalability   | Using Virtual machine scale sets         														| Using built-in service(Autoscaling)    												  |
| Availability  | Available time is from 95% to 99.95%     														| The App will be available 99.95% of the time     									      |
| Workflow      | Deployment will be more complicated because it involes the operation system such as OS update | Something like an operating system, hardware is not required, so deployment will be fast| 


Choice: Using Web App Service to deploy my app. Because:
		- my project does'nt required about the operating system. 
		- the price of Web App Service is cheaper than VM
		- Deployment using Web App Service is quicker than using VM
		


### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 
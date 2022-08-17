# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

- The cost of using VM is higher than App service.
- App service have constrains in comparison to VM in term of scalability
- The application deployment is easier in App Service
- VM offer developer more control over the enviroments and allow for more customization of the app's capability but App service very useful for teams with less manpower, and less experience with managing hardware 

- I have selected App service to deploy this application

- Reason : 
    + This is small app and only need a little configuarion
    + It's quite easy to deploy

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

Requirement : The application becomes more complexity and need more configuartions.

Solution : Change to use VM instead of App Service. So you can add more configuarions in VM
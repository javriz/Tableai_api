#Create new project with TSC

1. Creating new project
```
with server.auth.sign_in(tableau_auth):
    new_project = TSC.ProjectItem("project1","TSC_Starter")
    new_project = server.projects.create(new_project)
```
2. 
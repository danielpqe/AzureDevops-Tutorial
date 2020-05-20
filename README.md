# AzureDevops-Workflow
A complete tutorial for implement Azure Devops in any project

## 1. Summary

## 2. Basics
   - Git
   - Azure DevOps
     - Boards, Repos, Pipelines, Test Plans
## 3. Workflow
### General Workflow
![workflow](img/workflow.jpg)

0. Initial tasks, Clone the project in visual studio (Do this every time a repository is cloned)
   This will create a copy of the Master Branch in the Azure Repository to the local environment


- Go to https://dev.azure.com/v-oshere/ , repository section (<img src="img/repo_section.png" width="20">), click in clone options and then click in clone in Visual Studio option
   <div style="text-align:center"><img src="img/clone_option.png" width="200" ></div>
- Visual Studio will be opened, then click in the prompt to confirm the connection
  <div style="text-align:center"><img src="img/connect_vs.png" width="250" ></div>
- Then will see the home dasboard for visual studio, in the left side is the Solution Explorer where We can find all files related to work, in the right side is the Team Explorer where We can be sync with the Azure Repository, by default when clone a repository We will be in the "master" branch as We can see in the right bottom
<div style="text-align:center"><img src="img/vs.png" width="600" ></div>

1. Update local master branch

If is the first time you clone a repository it is already updated, files in the local environment are the same than the Azure Repository.
If not, every time a task is started the local master branch should be updated, to do that go to sync option on the Team Explorer window
 <div style="text-align:center"><img src="img/sync.png" width="200" ></div>
Then click en fetch, it will show all changes has been done in the Azure Repository that is not currently in your own master branch
<div style="text-align:center"><img src="img/fetch.png" width="200" ></div>

To merge this changes to your local master branch click in Pull

2. Create new branch


3. Save work done and create a pull request


4. Resolve conflicts



## 4. Policies
   - Managing  branches (branches by requirement,etc)
   - Pull requests policies (delete automatically a branch once its created, etc)
    
## 5. Feedback




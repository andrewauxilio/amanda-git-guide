# Basic Git Guide

### Setting Up 
1. Clone repository into your local PC 
<br>
`git clone <link>` 
2. Open the project in VSCode
3. Open the terminal (you should automatically be in the project's root folder if you opened the project in VSCode, otherwise change directory - `cd <insert directory name here>`)
4. Get latest remote repository changes. If you're already up to date it should let you know 
<br>
`git pull`

### Branches
##### Creating a new branch locally
<br> When you start a task you can easily create a branch on your local machine:
`git checkout -b new-branch-name`
<br> To push your new branch to the remote repository (follow the steps git provides if it's the first time pushing this new branch to remote):
`git push` 

##### Creating a new branch on GitHub:
After creating the branch in GitHub, you will need to update your local repository:
<br>
`git pull`
<br>
Then you can work on that new branch by checking out:
`git checkout newly-created-branch-from-github`

##### Going into an existing branch
`git checkout existing-branch-name`

##### Listing available branches
`git branch`
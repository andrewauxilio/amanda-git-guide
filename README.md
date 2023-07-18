# Basic Git Guide

### Setting Up 
1. Clone repository into your local PC 
`git clone <link>` 

2. Open the project in VSCode
3. Open the terminal (you should automatically be in the project's root folder if you opened the project in VSCode, otherwise change directory - `cd <insert directory name here>`)
4. Get latest remote repository changes. If you're already up to date it should let you know:
`git pull`

### Branches
##### Creating a new branch
`git checkout -b new-branch-name`

##### Going into an existing branch
`git checkout existing-branch-name`

#### Listing available branches
`git branch`
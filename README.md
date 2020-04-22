## Project Initialization Helper

**Note: These are instructions for Windows OS**

This repo is to help you speed up the process of creating your project repositories with the execution of just one command.
**Instead of ~~6-plus~~ git commands, just run 1 and be done with it!** 

### How to Install:
```
git clone "https://github.com/mronfire/git-init.git"
cd git-init
pip install -r requirements.txt
```

### Set-Up:
- In order to connect to GitHub and have a determined project folder, we need to make some environment additions...
```
Under System Variables add the following entries:
1. "projectDir" = project directory where you want repos to be saved
2. "gToken" = your github token which you can find in your GitHub account
```
- Also, we need to add the PATH of the repo so we can call **create** from anywhere in the command prompt...
```
Under System Variables, go to Path and add a new entry with the path of where you cloned the repo in your machine.
1. C:\"pathToDirectoryWhereRepoIsAt\git-init\
Example:
    - C:\%USERPROFILE%\git-init\
```

### Hot to Use:
```
create <project_name>
```


-----------------------------------------------
GIT 
Source control system
Version control system

GITHUB
Collaborate code
Multiple developers can work at a time.
Code Storage.

Steps

1. Create GIT Repository / Folder
> git init

2. Check the status of your files
> git status

3. Log your changes with command 
> git log

3. Put your project inside the repository

    Process to put project files in repository
    1. Tracking Area -> Staging Area => git add <fileName>/ git add .
    2. Staging Area -> Commited => git commit -m "Any message"
    3. Committed


4. Connect your git with github
> git remote add origin <github repo url>
    To check if connection is established
    > git remote

5. Send these files/commits to GITHUB
> git push testOrigin

6. show all branches
> git branch

7. Create a new branch
> git branch <branchName>

8. To go inside the branch
> git checkout <branchName>

9. To create and checkout 
-> git checkout -b <branchName>

10. Pull donation branch changes into main branch
> Go inside the branch where you want the changes to be reflected.
> git pull testOrigin donation

11. To get whole repository inside your local
> git clone <github repo clone>

Exit vim editor
:wq
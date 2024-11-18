# Ironhack_Week_1

**Day 1 GIT**

git init #To initialise git repository

git config --global user.name "Festus Chima" #To configure global username

git config --global user.email "festusinvitesu@gmail.com" #To configure global email address

git config --global --list #To list all the global variables

git config --global --unset-all user.name #To remove username

git config --global --unset-all user.name #To remove multiple entries of usernames

git add . #To add all the changes to the staging area

git status  #To check the status of your code repository

git commit -m "<your message>" #To commit changes to the local repository

git diff #To see the differences between the files in the working directory and the ones in the local repository

git log #Shows logs of files that you have earlier committed with detailed info

git log --oneline #Gives you logs in compressed manner

git branch #To see the list of branches

git branch <new_branch> #To create new branch

git checkout <branch_name> #To switch to the mentioned branch

git merge <feature_branch> #This merges the files from feature branch onto the current branch

git remote add origin <URL of the repository> #Connecting the local repo to the remote repo set to origin

git push --set-upstream origin main #Setting the remote repo (origin) as a default branch, from which files in "main" branch can be pushed

git fetch #This will fetch the updates from the remote repo without merging it to the local repo

git pull #This will fetch and merge the updates from the remote repo to the local repository.









# Git Commands and Notes

## Configuring Git

After installing Git, you can also configure it - most importantly, you can set a username and email address that will be connected to all your code snapshots.

This can be done via:

   * git config --global user.name "your-username"
   * git config --global user.email "your-email"

You can learn more about Git's configuration options here: <https://git-scm.com/docs/git-config>

## Commands

    * git init -> to initialize the local repo (creates metadata in .git folder)

    * git add <file_name>  -> to stage for next commit

    * git branch <branch-name> -> to create new branch

    * git checkout -b <branch-name> -> to create new branch and check it out automatically 

    * git branch -> to list available branches

    * git checkout to switch between branches or commits

    * git branch -D <branch-name> -> to delete a branch permanently

    * git merge <branch-name>  -> to merge branch-name to current branch

    * git remote add origin <url-to-remote-repo> -> to add remote git repository

    * git push origin <branch-name> -> to push the branch to origin

    * git remote set-url origin https://user-name@<url.git> -> to setup access to push code

    * git pull origin <branch-name> -> to pull down remote branch

    * git remote -> to list remote alias

    * git remote get-url origin -> to list the url for remote repo


## Undo Commits

    * git revert <id>  -> keeps history
    
    * git reset <id>  -> deletes history 

# Git Commands:

## Main:
- `git remote add origin repo_url`: used to add a remote url to your current project.
    - `origin` here is the name of the remote repo, you can change it to another one if you like.
- `git remote set-url origin repo_url`: used to change the remote url of your project, for example to change from https to ssh repo.
- `git remote -v `: used to show the remote urls. 
- `git status`: which files are untracked (modified stage) or tracked but not committed and so on.
- `git rest HEAD 'file'` it is used to revert, or rollback the changes which is not committed yet.
    - From tracked to untracked stages.
    - `git restore` can be used in newer versions of git.
    - `git push --set-upstream origin master` to set the default push branch to save time not specifying it every time.
- `git checkout -B branch_name`: used to create a new branch and checkout to it.
- `git branch branch_name`: used to create a branch.
- `git branch`: list all branches in current repo.
- `git branch -d branch_name`: delete a branch locally.
- `git push -u origin branch_name`: it is used to push date to the branch.
    - `-u` flag is used to set the up-stream so you can push directly later to this branch without specifying its name.


    


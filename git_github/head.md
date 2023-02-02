# HEAD:
### git always has a reference to the commit and branch you are working on. it is stored in the .git directory in the HEAD file. 

- when you view the head file content, it will show the reference id of the commit:
    - `cd .git` then `cat head` will give you the reference `refs/heads/master` which will contain the branch and if you view it it will contain the `latest commit id`. 
    - you can use this commit id to revert your changes to this commit.
# All About Git

- From branching, merging to conflict resolutions.


# Create a new branch from terminal

1. clone the master repo into a new folder
    - `git clone --recursive git@github.com:khanalg44/AllAboutGit.git new_branch`
2. Go inside the directory `new_branch`
    - `cd new_branch`
3. Create a branch 
    - `git branch new_branch`
4. Checkout to the new branch
    - `git chekout new_branch`
5. Now add a file (file1) and push it to remote.
    - `git add file1; git commit -m 'added new file'; git push`
6. Go to the directory with master branch and do git pull so that the master branch knows about the newly created branch `new_branch`
    - `cd <master_branch>; git pull`


# Merging the Master branch to a different branch

Once the local changes are commited and pushed you can merge the master to your branch.

1. Go inside the branch and merge the master branch
    - `git merge origin/main`
2. Push the changes to the remote.
    - `git push`


# Undoing the Commit 
1. Assuming the code is added annd already commited to the repo. The following will undo the commits without removing the local changes. (Stack Overflow link)[https://stackoverflow.com/questions/4114095/how-do-i-revert-a-git-repository-to-a-previous-commit]
    - `git reset HEAD~1`


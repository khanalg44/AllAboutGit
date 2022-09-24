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
    - cd <master_branch>; git pull

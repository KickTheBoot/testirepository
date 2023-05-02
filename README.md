# Getting Started with git
## Cloning a repository
the first thing you want to do when starting to work on a pre-existing repository is to clone it using the **git clone** -command:
>git clone \<remote-url\>

this clones the remote repository into a newly created folder inside the active directory.

## Initializing a repository
When you're starting from scratch, use the **git init** -command:
>git init

this initializes a git repository inside the active directory

## Creating branches
When starting to work on a new feature, it is wise to create a new branch using **git branch \<branch-name\>** to keep the main branch clean:
>git branch \<branch-name\>

alternatively you can create and switch to the new branch using **git checkout -b**:
>git checkout -b \<branch-name\>

this way, you'll automatically switch to the created branch.

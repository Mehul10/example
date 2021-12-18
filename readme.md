# Git and Github

## Git
```
Git is a version control system
```
### Why use Version Control?
1) Backup and Restore
    - Google docs
    - Files saved as edited
    - Jump back to changes

2) Synchronization
    - Share files
    - Multiple developers

3) Undo
    - Jump to last stable version
    - Correct old mistakes

4) History Tracking
    - See entire commit history from everyone
    - See why and how things were implemented

5) Sandboxing
    - Make changes in a different branch
    - Different enivronment
    - Can experiment

### GIT

``` 
made merging very fast 
```

### How does git work?

``` 
Repository- A folder (Project or directory)
```

### How to use git?
1) Clone
2) Initialize
3) Log

    - log shows all the commits made to a repository (oldest first)
```
git log     //shows the history of the repository
```
4) Commit
    - Each change is represented by a commit
5) Branch
    - Different version of same project
    ```
    git branch      //shows all the branches
    git checkout bname      //changes the branch
    ```
6) Merge
    - To incorporte the changes into the main branch
    ```
    git checkout stable
    git merge master
    ```

## Installing Git
    https://git-scm.com/downloads    

## Github

1) Create new repo on github, push, commit
``` 
git init
git remote add origin https://github.com/Mehul10/example        //adds a new remote for this repo
git add
git commit -m "first commit"
git push origin master      //pushes to origin that is the repo and pushes to the master branch

```
2) Clone a repository

github-repo/abc

Clone it into my github account

Mehul10/abc
```
Go to the repo and click fork
```
Clone the forked repo into your PC :-
```
git clone [url]
```

You don't need to git remote add origin as when you clone the origin is of course all ready added, you need to push to the repo simply.

Now you can create a pull request to the owner of the original repo to add you changes to the original repo.

It is the same as the merging of the branches.

The admin will then merge the pull request if he thinks everything is okay.

## Google Summer of Code (GSOC)
 
    


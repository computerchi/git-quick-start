# Git Quick Start ![alt text](logo.jpg "GitHub")

by Ali Mahdi
2018-10-12

## Creat new project

Go to the _github.com_ site and create a new repo with an automatic readme.md file.

## Create a local copy

From the _github.com_ site copy the git _url_. From your PC type

```
>git clone <url>  // paste the url of the repo from github
>cd <repo-folder>        // change to the newly created project
>code .           // start editing the project
```

## Check current status

Check the status and differences between github and local repo on your PC type

```
>git status
```

## Update local repo

To receive the files of the repo from github to your PC type

```
>cd <repo-folder>
>git pull
```

**Note:** Now you are ready to make changes to the local repo folder on your PC. You can add files and folders as required.

## Save your changes to the main repo

After you've made changes, additions and deletions you are ready to add them to the repo. Type

```
>git add .  // to add all of the changes, or
>git <file> // to add a specific file.
>git commit -m "describe changes"
>git push
```

## Adding new feature to your app

To add new features to a stable app it is better to fork off a new branch. This cane be done from the _github.com_ site. After creating the branch change to the new branch on the local PC, type

```
>git checkout <new-branch>
>git branch -a // lists all the available branches and show the active branch.
```

Now make your changes then type

```
> git add .
> git commit -m "describe changes"
> git push
> git merge <master-branch>
```

Alternatively, you can create a _pull request_ and do the merging on the _github.com_ site. You still need to `add`, `commit`, and `push` first.

For more on github and the git command visit [the official _GitHub_ site](https://guides.github.com/).
![alt text](biglogo.png "GitHub")

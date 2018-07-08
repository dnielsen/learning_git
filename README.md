# learning_git
resources to help you learn git

Geting Started
- https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository

Create New Repo from My Folder
```
$ cd /Users/user/my_folder
$ git init
$ git add *.c
$ git add LICENSE
$ git commit -m 'initial project version'
```
Add new files:
```
$ git add README
$ git add *.c
$ git add *
```

Creating Project based on existing Repo
```
$ git clone https://github.com/libgit2/libgit2 mylibgit
```

Push changes back to master:
```
$ git add *.c
$ git commit -m 'initial project version'
$ git push
```

Delete a file:
- https://stackoverflow.com/questions/2047465/how-can-i-delete-a-file-from-git-repo

Other:
- .gitignore

## Git  commands

### Create a local git repository

```shell
$ mkdir myproject # this will create a directory.
$ cd myproject # this will go to myproject directory.
$ git init # this will initialize myproject directory as a git repo.
 ```

 ### How to check if git git init worrked or not?
 ```shell
$ git branch # we can use this command to check it is working or not in my current dir.
 ```

### Create a file

 ```shell
$ touch new.txt # this will create a file in myproject git repo.
$ echo "message" > file_name # this will add line in file.
 ```

### Create a new repository on the command line
echo "# test-repo" >> README.md
```shell
$ git init
$ git add README.md
$ git commit -m "first commit"
$ git branch -M main
$ git remote add origin git@github.com:shikha1108/test-repo.git
$ git push -u origin main

# we can use these commands to set a remote in local repo for git.
```

### Push an existing repository from the command line
```shell
$ git remote add origin git@github.com:shikha1108/test-repo.git  #this will set a remote in myproject repo.
$ git branch -M main  # this will change the master branch name in main.
$ git push -u origin main # this will use to push code in git hub. 
```
### How to check if git remote is set or not?
```shell
$ git remote -v
```
### To check branches
```shell
$ git branch  # this will display all the branches in terminal.
```
### Switch to another branch
``` shell
$ git checkout branch_name  # this command will use to switch other branches.
```

### create a new branch
```shell
$ git checkout - b branch_name  # this command will create a new branch.
```
### add file in git repo
```shell
$git add file_name  # this command will add file in repo.
```

### commit code
```shell
$git commit -m "message"   # this command will commit code in github.
```

### push code
```shell
$git push origin main    # this command is used to push the code in git repo.
```
### git log
```shell
$git log #this command will display all the commit
```

### how to undo commit
```shell
$git reset HEAD~1 #this command will undo one last one commit in the current branch.

$git reset HEAD~2#this command will undo one last two commit in the current branch.

```
### how to again push in git hub after undo commit
```shell
$git push -f origin main # this command will use after undo commit only.
```

### how to undo one file 
```shell
$git revert file_id # this command will undo the given file.
```
### how to pull the changes from main
```shell
$ git pull origin main. # this command is used to pull the chages from branch.
```


## Git  commands

### Create a local git repository

```shell
$ mkdir myproject # this will create a directory.
$ cd myproject
$ git init # this will initialize myproject directory as a git repo.
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

#we can use these commands to set a remote in local repo for git.
```

### Push an existing repository from the command line
```shell
$ git remote add origin git@github.com:shikha1108/test-repo.git  #this will set a remote in myproject repo.
$ git branch -M main  # this will change the master branch name in main.
$ git push -u origin main # this will use to push code in git hub. 
```
### To check branches
```shell
$ git branch  # this will display the branches in terminal.
```
#### Switch to another branch
``` shell
$ git checkout branch_name  # this command is used to switch branches.
```

### create a new branch
```shell
$ git checkout - b branch_name  # this command will create a new branch.
```
### add file in git repo
```shell
git add file_name  # this command will add file in repo.
```

### commit code
```shell
git commit -m "message"   # this command will commit code in github.
```

### push code
```shell
git push origin main    # this command is used to push the code in git repo.
```


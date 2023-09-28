## Git  commands

### Create a local git repository

```shell
$ mkdir myproject # this will create a directory.
$ cd myproject
$ git init # this will initialize myoroject directory as a git repo.
 ```

### Create a file with touch command

 ```shell
 touch new.txt # this will create a file in myproject git repo.
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

#we can use these command to set a remote in local repo for git.
 
```

*  push an existing repository from the command line
```git
git remote add origin git@github.com:shikha1108/test-repo.git
git branch -M main
git push -u origin main
#this will set a remote in myproject repo.
```
* check branch
```git 
git branch
# this will create display the branches in terminal.
```
* checkout to main branch
``` git 
git checkout main
# this will took in main branch
```

* create a new branch
```git
git checkout - b feature
# this will create a new branch.
```
* add file in git repo
```git
git add file_name
# this will add file in repo.
```

* commit code
```git
git commit -m "message"
# this command will commit code in github.
```

* push code
```git
git push origin main
#c this command is used to push the code in git repo.
```


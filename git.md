## Git  commands

* create a local git repository
```git
mkdir myproject 
```
* use cd 
```git
cd myproject
```
 * to initialize a git repository in the repo use git init
 ```git
 git init
 ```
 * initialize a empty git repository with myproject

 * create a file with touch command
 ```git 
 touch new.txt
 ```
* create a new repository on the command line
echo "# test-repo" >> README.md
```git
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:shikha1108/test-repo.git
git push -u origin main
```

*  push an existing repository from the command line
```git
git remote add origin git@github.com:shikha1108/test-repo.git
git branch -M main
git push -u origin main
```
* check branch
```git 
git branch
```
* checkout to main branch
``` git 
git checkout main
```

* create a new branch
```git
git checkout - b feature
```
* add file in git repo
```git
git add file_name
```

* commit code
```git
git commit -m "message"
```

* push code
```git
git push origin main
```


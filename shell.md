# Shell scripting

## Commands

* List all files in a directory
```shell
$ ls
Example:
 $ ls ~/Documents   # list the files in documents directory.
 $ ls -l ~/Documents   # list the files with details in documnets directory.
```
* Change to a directory
cd
```shell
Example:
$ cd  # go to root. 
$ cd ~   # go to home directory.
$ cd dir1  # go to dir1.
```

* Move a directory
```shell
mv file_name #this command will move file
```

```shell 
$ mv ~/Documents/dir_name  ~/Downloads   # move a directory to another path directory with absolute path.

$ mv vegie3.txt ../../Documents    # move a directory to another path directory (from downlods) with relative path. 

$ mv -r ~/Documents/test ~/Downloads  # this command will move test dir along with all its files to ~/Downloads.
```

* Remove a directory
```shell
$ rm -r dir_name   #remove a directory along with files.
$ rm new.txt   #this commnad will remove file.
```

```shell
$ rm -r /Users/shikha/Downloads/vegetable  # remove a diectory vegetable from Downlods directory.
```

* Copy a file or directory 
```shell
$ cp ~/Documents/abc.txt ~/Downloads/abc.txt #this command will copy abc.txt from ~/Documents to ~/Downloads.
$ cp -r ~/Documents/test ~/Downloads/test #this command will copy test dir along with all its files to ~/Downloads.
```

* Display a content of a file
```shell
$ cat hello.txt   #it is used to Display the contents of a file
```
* Display the current or working directory.
```shell
$ pwd     #the `pwd` command will display the absolute path of the current directory.
```

* add content in a file
```shell
#we use `echo` to print the message "Hello, World!" to the terminal.
$ echo "Hello, World!"
```

* Redirect output to a file
```shell
$ echo "This is a message" > output.txt  #this will write the message "This is a message" to a file named output.txt.
```
* How to check hidden file in a repository
```shell
$ ls -a
```

* Search for patterns in files(grep)
```shell
$ grep hello file_name # this command will display the pattern of hello in this file.
```


* Count word in a file
```shell
$ wc -l new.txt  # it will count all the lines in new.txt file.
```

* pipe
```shell
$ cat file_name | wc -l  # it will make the first argument to another output with the help of pipe.
```

* head
```shell
$ head -n 5 example.txt # it will display the first 5 lines of a  example.txt file.
```

* tail
```shell
$ tail -n 2 example.txt  # it will display the last 5 lines of a  example.txt file.
```

* uniq
```shell
$ new.txt wc -l | uniq  #this command will find unique data from new.txt file
```






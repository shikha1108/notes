# Shell scripting

## Commands

* List all files in a directory
```shell
ls
Example:
list the files in documents directory: ls ~/Documents
ls -l
list the files with details in documnets directory: ls -l ~/Documents
```
* Change to a directory
cd
```shell
Example:
Go to root: cd /
Go to home directory: cd ~
Go to dir1: cd dir1
```

* Move a directory
`mv`

Example:
```shell
# move a directory to another path directory with absolute path  
mv ~/Documents/dir_name  ~/Downloads

# move a directory to another path directory (from downlods) with relative path 

mv vegie3.txt ../../Documents

# this command will move test dir along with all its files to ~/Downloads

mv -r ~/Documents/test ~/Downloads
```

* Remove a directory
`rm -r`

Example:
```shell
remove a diectory vegetable from Downlods directory.
rm -r /Users/shikha/Downloads/vegetable
```

* Copy a file or directory 
```shell
cp
We can use `cp` command to copy a file or directory.
```

Examples
```shell
cp ~/Documents/abc.txt ~/Downloads/abc.txt #this command will copy abc.txt from ~/Documents to ~/Downloads
cp -r ~/Documents/test ~/Downloads/test #this command will copy test dir along with all its files to ~/Downloads
```

* Display a content of a file
`cat`

It is used to Display the contents of a file.

* Display the current or working directory.
```shell
pwd

The pwd command will display the absolute path of the current directory.
```

* add content in a file
```shell
echo
We use echo to print the message "Hello, World!" to the terminal.
echo "Hello, World!"
```

Redirect output to a file
```shell
echo "This is a message" > output.txt
```
This will write the message "This is a message" to a file named output.txt.

* Search for patterns in files(grep)
```shell
Example: 
grep hello file_name
# this command will display the pattern of hello in this file.
```


* Count word in a file
```shell
wc -l new.txt
# it will count all the lines in new.txt file.
```

* pipe
```shell
cat file_name | wc -l
# it will make the first argument to another output with the help of pipe.
```

* head
```shell
head -n 5 example.txt
# it will display the first 5 lines of a  example.txt file.
```

* tail
```shell
tail -n 2 example.txt
# it will display the last 5 lines of a  example.txt file.
```

* uniq
```shell
new.txt wc -l | uniq

```






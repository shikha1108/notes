# Shell scripting

## Commands

* List all files in a directory
`ls -l`
Example:
list the files in documents directory: `ls ~/Documents`
list the files with details in documnets directory: `ls -l ~/Documents`

* Change to a directory
`cd`
Example:
Go to root: `cd /`
Go to home directory: `cd ~`
Go to dir1: `cd dir1`

* Move a directory
`mv`
Example:
move a directory to another path directory with absolute path`mv  /Users/shikha/Documents/dir_name  /Users/shikha/Downloads`
move a directory to another path directory (from downlods) with relative path `mv vegie3.txt ../../Documents`

* Remove a directory
`rm -r`
Example:
remove a diectory vegetable from Downlods directory.
`rm -r /Users/shikha/Downloads/vegetable`

* Copy a file or directory 
We can use `cp` command to copy a file or directory.
Examples
```shell
cp ~/Documents/abc.txt ~/Downloads/abc.txt #this command will copy abc.txt from ~/Documents to ~/Downloads
cp -r ~/Documents/test ~/Downloads/test #this command will copy test dir along with all its files to ~/Downloads
```

* Display a content of a file
`cat`
It is used to Display the contents of a file.

* Display the current or working directory
`pwd` The pwd command will display the absolute path of the current directory.

* add content in a file
`echo`
We use echo to print the message "Hello, World!" to the terminal.
`echo` "Hello, World!"

Redirect output to a file
`echo` "This is a message" > output.txt
This will write the message "This is a message" to a file named output.txt.

* Search for patterns in files
`grep`
Example: 


* Count word in a file
`wc -l`

* pipe
cat file_name | wc -l
cat file_name | wc-l | uniq

* head

* tail

* uniq






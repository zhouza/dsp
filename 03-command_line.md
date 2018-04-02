# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> > pwd - displays path of current working directory

> > mkdir <directory> - creates a directory named <directory>
  
> > rm -r <directory> - deletes <directory> by deleting recursively
  
> > touch <file> - creates <file> if it doesn't exist; otherwise updates file access and modification time
  
> > rm <file> - deletes <file>
  
> > mv <old_file> <new_file> - renames <old_file> to <new_file>

> > ls -a - lists all including hidden files

> > cp <file> <directory> - copy <file> to <directory>
  
> > mv <file> <directory> - move <file> to directory>
  
> > cat <file> - show the contents of <file> in the output

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> > ls lists files in the directory

> > ls -a lists all files

> > ls -l lists long format

> > ls -lh lists long format with readable file size

> > ls -lah lists long format including hidden files with readable file size

> > ls -t lists files sorted by time and date

> > ls -Glp lists files in a long listing with / indicator to directories without printing group names

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > -c displays files by file timestamp

> > -r displays files in reverse order

> > -t displays newest files first by timestamp

> > -m displays the names as a comma separated list

> > -1 displays each entry on a line

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > xargs reads items from standard input separated by spaces and executes a command for each of the items

> > in the below example, directories are created for each of the input names 

> > echo 'dir1 dir2 dir3' | xargs mkdir


# Create, Delete, Copy and Move Files and Directories
Linux organizes files in a file system tree. The root of the file system is 
the '/' there can be no other files above it. Under the root there are 
subdirectories such as home, var and so on. To get to a directory or file you 
must specify its path.

### Absolute paths vs Relative paths
*Absolute* paths always start with the root of the file system '/' followed by
the subdirectories.

Example:
/home/aaron/Documents/Invoice.pdf


*Relative* paths are **relative** to your current directory. To see your 
current directory you can use the following command:

*pwd - print working directory*
```
$ pwd
``` 



### Changing directories
To change your current working directory use the cd command followed by the 
path relative or absolute.

*absolute path*
```
$ cd /home/aaron
```


*relative path*
```
$ cd Documents/Invoice.pdf
```



**Note** that two dots '..' can also be used to move between directories. 
'..' means move to the parent directory of the current directory. 
	
*Usage*
```
$ cd ../../
```
move two directories above your current directory.



### Listing the contents of a directory
To see what is inside your current directory use the 'ls' command. 'ls' 
without any arguments will default to the current directory. You can also 
provide the path to a directory outside the current directory using a relative
path or a absolute path.

*current directory*
```
$ ls
```

<br/>
List contents at absolute path

```
$ ls \home\aaron\Documents\
```

<br/>
Common flags

-a list all files including hidden files <br/>
-l list files in long format <br/>
-h human readable statistics on files must be used with '-l' flag

**Note** multiple flags can be combine 


*Example*
```
$ ls -alh
```

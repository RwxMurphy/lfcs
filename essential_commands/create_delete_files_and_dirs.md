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


*Relative* paths are **relative** to your current directory. To see your current 
directory you can use the following command:

	```bash
	$ pwd
	```
	pwd - print working directory 

### Changing directories
To change your current working directory use the cd command followed by the 
path relative or absolute.

	```bash
	$ cd /home/aaron
	```
	*absolute path*

	```bash
	$ cd Documents/Invoice.pdf
	```
	*relative path*


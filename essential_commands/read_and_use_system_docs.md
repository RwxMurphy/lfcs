# System Documentation

### --help
To get help with a specific command you can use the --help option. This will 
give you information on how to use the command and its availale options.

*Usage*

```bash
$ ls --help
```


### man pages
man short for manual provides detailed information on a command such as a the 
name, synopsis, description, usage etc. Manual pages are usually opened in a 
pager that allows you to 'page' through the content using the arrow keys or 
page-up and page-down keys. To exit press 'q'.

*Usage*

```bash
$ man journalctl
```

**Note** the man pages are devided into different sections, some commands can 
be found in multiple sections in most cases commands for administering the 
system are found in section 1 and section 8. to show only these sections:

```bash
$ man 1, 8 journalctl
```


## Apropos
If you do not know which command you would like to use, you can use the 
apropos command to search the man pages description to find a command that 
matches you description.

```bash
$ apropos director
```

This will return results from all sections of the manual that has a match. To 
fine tune your results with only items from section 1 and 8 use.

```bash
$ apropos -s 1, 8 director
```

This command depends on a database to function, if the machine is newly 
created the database will need to be manually created.

```bash
$ sudo mandb
``` 

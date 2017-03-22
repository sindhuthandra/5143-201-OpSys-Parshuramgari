#                                     DATE : 2/21/2017
#                                    TITLE : SHELL PROJECT
#PROJECT DESCRIPTION :This program implements shell commands cat,chmod,cd,cd ..,etc as in the below list 
                      Note:code written in python
                      execution command: python driver.py
                      implementation:give the commands one by one after the % sign
                      geting out of shell:give "exit" command for quiting from shell

#IMPLEMENTED COMMANDS 


| Command	     | Flag / Param      | Meaning                      |
|----------------|------------|-----------------------------------|
| `ls	`        |            | list files and directories        |
|                |    `-a`	  |   list all show hidden files      |
|                |    `-l`	  |    long listing                   |
|                |    `-lh`	  |long listing    human readable sizes           |
|                |    `-la`	  |    long listing including hidden files                  |
|                |     `-lah`| longlisting of all files including hidden with human readable sizes|
| `mkdir`	     |             |make a directory                  |
| `cd`           |  `directory` |change to named directory         |
| `cd`	         |             |change to home-directory          |
|                |   `~	`      |change to home-directory           |
| 	             |   `..`      |change to parent directory          | 
| `pwd`	         |             |display the path of the current directory |



| Command | Params      |Meaning                                  |
|---------|-----------|-------------------------------|
| `cp `            | `file1 file2`    | copy file1 and call it file2 |
| `mv`             | `file1 file2`    | move or rename file1 to file2 |
| `rm`             | `file`           | remove a file |
| `rmdir`             | `directory`  | remove a directory |
| `cat`             | `file` | display a file |
| `less`             | `file` | display a file a page at a time |
| `head`             | `file` | display the first few lines of a file |
| `tail`             | `file` | display the last few lines of a file |
| `grep`             | `'keyword' file` | search a file for keywords |
| `wc`             | `file` | count number of lines/words/characters in file |

| Command | Meaning      |
|--------------------------|---------|
| `command > file`           | redirect standard output to a file |
| `command >> file`          | append standard output to a file |
| `command < file`           | redirect standard input from a file |
| `command1 | command2`      | pipe the output of command1 to the input of command2 |
| `cat file1 file2 > file0`  | concatenate file1 and file2 to file0 |
| `sort`                     | sort data |
| `who`                      | list users currently logged in |

| Command | Meaning |
|--------------------------|---------|
| `history`           | show a history of all your commands |
| `!x`                | this loads command `x` from your history so you can run it again |
| `chmod xxx`         | change modify permission | 

#command not implemented or not working as intended
#->chmod working ,but dont change the permisions as intended.Trying to fix that
#->& after command ,have trying, but not implemented in this project by this time 
>Group Members
>
| Name     | Email   | Github Username |
|----------|---------|-----------------|
| AJAY DINAKAR KANDAVALLI   | ajaydinakar6@gmail.com | ajaydinakar |
| SAIKIRAN REDDY NAGULAPALLY  | saikiranreddy791@outlook.com| saikiranreddy-nagulapally |
| THIRUPATHI REDDY PARSHURAMGARI  | thirupathi.idks126@gmail.com | thirupathireddy-parshuramgari |

#REFERENCES
#->http://stackoverflow.com
#->https://docs.python.org/2/library/os.html
#->for colors  https://www.youtube.com/watch?v=TvOKST5A6kI
#->https://docs.python.org/2/library/shutil.html
#->https://docs.python.org/2/library/os.html @used while doing 'ls' function



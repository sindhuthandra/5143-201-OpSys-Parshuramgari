#DATE : 2/21/2017
#TITLE : SHELL PROJECT
#PROJECT DESCRIPTION :This program implements shell commands cat,chmod,cd,cd .., cd ~, cp,ls including -l,-s,-a,-m,-c, mv, rm,wc and wc -l commands.
#IMPLEMENTED COMMANDS 
| Command | Flag/Param   | Meaning |
|----------|---------|-----------
| ls       |         |list files and dirrectories|
| mkdir    |         |make a directory     |
|cd|directroy|change to named directory|
||~|change to homoe directory|
|cd||change to home directory|
||..|change to parent directory|
|pwd||display the path of current directory|

|Command |Params|Meaning|
|--------|------|-------|
|cp|file1 file2|copy file1 and call it file2|
|mv|file1 file2|move or rename file1 to file2|
|rm|file|remove a file|
|rmdir|directory|remove a directory|
|cat |file|display a file|
|head|file|dispaly the first few lines of a file|
|tail|file|display the last few lines of a file|
|grep|'keyword' file|search a file for keywords|
|wc|file|count number of lines/words/characters in file|
|who| |list useres currently logged in|
|history||show a history of all your commands|
|chmod xxx||change modify permission|

#Unimplemented commands
|Command|Flag/Param/|Meaning|
|--------|----------|-------|
|ls |-a|list all show hidden file|
||-l|long listing|
||-h|human readable sizes|
|less|file|display a file a page at a time|
|command > file||redirect standard output to a file|
|command >> file| |append standard output to a file|
|commmand < file||redirect standard input from a file|
|command1 command2| | pipe the output of command1 to the input of command2|
|cat file1 file2 > file0||concatenate file1 and file2 to file0|
|sort ||sort data|
|!x||this loads command x from your history so you can run it again|

#Group Members
| Name     | Email   | Github Username |
|----------|---------|-----------------|
| Thirupathi Reddy Parshuramgari | thirupathi.idks126@gmail.com |  thirupathireddy-parshuramgari |
| Saikiran Reddy Nagulapally  | saikiranreddy791@outlook.com | saikiranreddy-nagulapally |
| Ajay Dinakar Kandavalli | ajaydinakar6@gmail.com| ajaydinakar |

#REFERENCES
#http://stackoverflow.com
#https://docs.python.org/2/library/os.html
#https://docs.python.org/2/library/shutil.html




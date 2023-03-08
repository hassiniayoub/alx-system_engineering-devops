In this file we will explain what each script is doing

0-current_working_directory \n
=> this script prints the absolute path name of the current working directory

1-listit
=> this script display the contents list of your current directory.

2-bring_me_home
=> this script changes the working directory to the user’s home directory.

3-listfiles
=> this script display current directory contents in a long format

4-listmorefiles
=> this script display current directory contents, including hidden files (starting with .). using the long format.

5-listfilesdigitonly
=> this script display current directory contents. (Long format, with user and group IDs displayed numerically, And hidden files (starting with .))

6-firstdirectory
=> this script creates a directory named my_first_directory in the /tmp/ directory.

7-movethatfile
=> this script move the file betty from /tmp/ to /tmp/my_first_directory.

8-firstdelete
=> this script delete the file betty. (The file betty is in /tmp/my_first_directory)

9-firstdirdeletion
=> this script delete the directory my_first_directory that is in the /tmp directory.

10-back
=> this script changes the working directory to the previous one.

11-lists
=> this script lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

12-file_type
=> this script prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.

13-symbolic_link
=> this script create a symbolic link to /bin/ls, named __ls__. The symbolic link created in the current working directory.

14-copy_html
=> this script copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

100-lets_move
=> this script moves all files beginning with an uppercase letter to the directory /tmp/u.

101-clean_emacs
=> this script deletes all files in the current working directory that end with the character ~.

102-tree
=> this script creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory. without using two spaces (and lines) in the script

103-commas
=> this script has a command that lists all the files and directories of the current directory, separated by commas (,)

school.mgc
=> this magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.

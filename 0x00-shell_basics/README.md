0-current_working_directory contains a script that prints the absolute path name of the current working directory.

1-listit displays the contents list of your current directory.

2-bring_me_home contains a script that changes the working directory to the user’s home directory.

3-listfiles contains a script that displays current directory contents in a long format.

4-listmorefiles contains a script that displays current directory contents, including hidden files (starting with .). Use the long format.

5-listfilesdigitonly contains a script that displays current directory contents.

6-firstdirectory contains a script that creates a directory named my_first_directory in the /tmp/ directory.

7-movethatfile contains a script that moves the file betty from /tmp/ to /tmp/my_first_directory.

8-firstdelete contains a script that deletes the file betty.

9-firstdirdeletion contains a script that deletes the directory my_first_directory that is in the /tmp directory.

10-back contains a script that changes the working directory to the previous one.

11-lists contains a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

12-file_type contains a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.

13-symbolic_link containes a script that creates a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.

14-copy_html containes a script that creates a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

100-lets_move containes a script that creates a script that moves all files beginning with an uppercase letter to the directory /tmp/u.

101-clean_emacs containes a script that creates a script that deletes all files in the current working directory that end with the character ~.

102-tree containes a script that creates a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.

103-commas containes a script that lists all the files and directories of the current directory, separated by commas (,):
  Directory names should end with a slash (/)
  Files and directories starting with a dot (.) should be listed
  The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
  Only digits and letters are used to sort; Digits should come first
  The listing should end with a new line
  
school.mgc can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.

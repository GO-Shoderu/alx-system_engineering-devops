These are the list of scripts and what they do respectively

NB: Before running any scripts please execute the command below for each respective scripts

chmod u+x name_of_script
	- for example: chmod u+x 1-listit

0-current_working_directory
	- this script prints the current working directory
	- run the command above before running the script as stated in NB
	- you will need to execute the code below to test the script
		./0-current_working_directory

1-listit
	- this script prints the list of files or directories in the current working directory
	- run the command above before running the script as stated in NB
	- you will need to execute the code below to test the script
		./1-listit

2-bring_me_home
	- this script changes the working directory to the user's home directory
	- run the command above before running the script as stated in NB
	- you will need to execute the code below to test the script
		./2-bring_me_home

3-listfiles
	- this script list the files and directories in a long format
	- run the command above before runing the script as stated in NB
	- you will need to execute the code below to test the script
		./3-listfiles

4-listmorefiles
	- this script list the files and directories in a long format including hidden files
	- run the command above before running the script as stated in NB
	- you will need to execute the code below to test the script
		./4-listmorefiles

5-listfilesdigitonly
	- this script list the files and directories in a long format including hidden files with user and group IDs displayed numerically
	- run the command above before runing the script as stated in NB
	- you will need to execute the code below to test the script 
		./5-listfilesdigitonly

6-firstdirectory
	- this script creates a directory called my_first_directory in the tmp folder at the root 
	- run the command above before running the script as stated in NB
	- you will need to execute the code below to test the script
		./6-firstdirectory

7-movethatfile
	- this script moves any file named betty in the tmp folder at the root to the folder called my_first_directory in tmp folder at the root
	- run the command above before running the script as stated in NB
	- you will need to execute the code below to test the script
		./7-movethatfile

8-firstdelete
	- this script will delete any file named betty in the my_first_directory folder in the tmp folder at the root
	- run the command above before running the script as stated in NB
	- you will need to execute the code below to test the script
		./8-firstdelete

9-firstdirdeletion
	- this script will delete any folder called my_first_directory in the tmp directory at the root
	- run the command above before running the script as stated in NB
	- you will need to execute the code below to test the script
		./9-firstdirdeletion

10-back
	- this script will change the working directory to the previous one
	- run the command above before running the script as stated in NB
	- you will need to execute the code below to test the script
		./10-back

11-lists
	- this script will list the files in the current directory, parent directory of the currrent directory and also the boot directory at the root
	  these lists will also include hidden files and the listed files will be in long format as well
	- run the command above before running the script as stated in NB
	- you will need to execute the code below to test the script
		./11-lists

12-file_type
	- this script will print the file type of a particular file called iamafile in the temp directory at the root
	- run the command above before running the script as stated in NB
	- you will need to execute the code below to test the script
		./12-file_type

13-symbolic_link
	- this script will create a symbolic link
	- run the command above before running the script as stated in NB
	- you will need to execute the code below to test the script 
		./13-symbolic_link

14-copy_html
	- this script will copy files that does not exist in the destination directory or files that have newer version than in the destination directory
	- run the command above before running the script as stated in NB
	- you will need to execute the code below to test the script
		./14-copy_html

100-lets_move
	- this script will move all the files beginning with an uppercase letter to a folder called u in the tmp folder in the root 
	- run the command above before running the script as stated in NB
	- you will need to execute the code below to test the script
		./100-lets_move

101-clean_emacs
	- this script will move all the files ending with a character ~ in the current working directory
	- run the command above before running the script as stated in NB
	- you will need to execute the code below to test the script
		./101-clean_emacs

102-tree
	- this script will generate child, grand child and great grand child directories, welcome, to and school in that order
	- run the command above before running the script as stated in NB
	- you will need to execute the code below to test the script
		./102-tree

103-commas
	- this script will list the items in the directory in order and seperated by commas and will also include hidden files
	- run tis command above before running the scripts as stated in NB
	- you will need to execute teh code below to test the script
		./103-commas

school.mgc
	- this script will be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0
	- it is created before compilation with 
		0 string SCHOOL School data
		!:mime School
	- it is compiled with the below
		file -C -m school.mgc

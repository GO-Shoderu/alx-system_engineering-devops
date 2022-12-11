These are the list of scripts and what they do respectively

NB: Before running any scripts please execute the command below for each respective scripts
	
	chmod u+x name_of_script
		- for example: chmod u+x 1-listit
	
	0-Hello-world
		- this script displays hello
		- you will need to execute the code below to test the script
			./0-Hello_world

	1-confused_smiley
		- this script displays a confused smiley "(Ôo)'
		- you will need to execute the code below to test the script 
			./1-confused_smiley

	2-hellofile
		- this script displays the content of /etc/passwd file
		- you will need to execute the code below to test the script
                        ./2-hellofile

	3-twofiles
                - this script displays the content of /etc/passwd and /etc/hosts files simulteanously
                - you will need to execute the code below to test the script
                        ./3-twofiles

	4-lastlines
                - this script displays the last 10 lines of the content of /etc/passwd file
                - you will need to execute the code below to test the script
                        ./4-lastlines

	5-firstlines
                - this script displays the first 10 lines of the content of /etc/passwd file
                - you will need to execute the code below to test the script
                        ./5-firstlines

	6-third_line
                - this script displays the third lines of the content of iacta file
                - you will need to execute the code below to test the script
                        ./6-third_line

	7-file
                - this script writes Best School into a file \*\\'"Best School"\'\\*$\?\*\*\*\*\*:)
                - you will need to execute the code below to test the script
                        ./7-file

	8-cwd_state
                - this script writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, it creates it.
                - you will need to execute the code below to test the script
                        ./8-cwd_state

	9-duplicate_last_line
                - this script duplicates the last line of the file iacta
                - you will need to execute the code below to test the script
                        ./9-duplicate_last_line

	10-no_more_js
                - this script deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
                - you will need to execute the code below to test the script
                        ./10-no_more_js

	11-directories
                - this script counts the number of directories and sub-directories in the current directory.
                - you will need to execute the code below to test the script
                        ./11-directories

	12-newest_files
		- this script will display the 10 newest files in the current working directory.
		- you will need to execute the code below to test the script 
			./12-newest_files
	
	13-unique
		- this script will take a list of words as input and print only words that appear exactly once.
		- you will need to execute the code below to test the script
			cat list | ./13-unique
			
	14-findthatword
		- this script will display lines containing the pattern root from the file /etc/passwd
		- you will need to execute the code blow to test the script
			./14-findthatword
			
	15-countthatword
		- this script will display the number of lines that contain the pattern "bin" in the file /etc/passwd
		- you will need to execute the code blow to test the script
			./15-countthatword
			
	16-whatsnext
		- this script will display lines containing the pattern "root" and 3 lines after them in the file /etc/passwd
		- you will need to execute the code blow to test the script
			./16-whatsnext
			
	17-hidethisword
		- this script will display all the lines in the file /etc/passwd that do not contain the pattern "bin"
		- you will need to execute the code blow to test the script
			./17-hidethisword
	
	18-letteronly
		- this script will display all lines of the file /etc/ssh/sshd_config starting with a letter
		- you will need to execute the code blow to test the script
			./18-letteronly
			
	19-AZ
		- this script will replace all characters A and c from input to z and e respectively
		- you will need to execute the code blow to test the script
			echo 'Replace all characters `A` and `c` from input to `Z` and `e`.' | ./19-AZ
			
	20-hiago
		- this script will remove all letters c and C from input
		- you will need to execute the code blow to test the script
			echo Chicago | ./20-hiago 
			
	21-reverse
		- this script will reverse it input
		- you will need to execute the code blow to test the script
			echo "Reverse" | ./21-reverse
			
	22-users_and_homes
		- this script will display all users and their home directories and will be sorted by users
		- you will need to execute the code blow to test the script
			./22-users_and_homes
			
	100-empty_casks
		- this script will find all empty files and directories in the curent directory and all subdirectories
		- you will need to execute the code blow to test the script
			./100-empty_casks
			
	101-gifs
		- this script will list all the files with a .gif extension in the current directory and all its subdirectories
		- you will need to execute the code blow to test the script
			./101-gifs
			
	102-arcostic
		- this script will decode arcostics that use the first letter of each line
		- you will need to execute the code blow to test the script
			./102-acrostic < An\ Acrostic 
ELIZABETH

	103-the_biggest_fan
		- this script will pars webservers logs in TSV format as input and display the 11 hosts or IP addresses which did the most reqests
		- you will need to execute the code blow to test the script
			./103-the_biggest_fan < nasa_19950801.tsv 

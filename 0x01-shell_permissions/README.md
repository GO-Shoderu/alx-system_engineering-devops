These are the list of scripts and what they do respectively

NB: Before running any scripts please execute the command below for each respective scripts

chmod u+x name_of_script
	- for example: chmod u+x 1-listit

0-iam_betty
	- this script switches the current user to the user betty
	- you will need to execute the code below to test the script
		./0-iam_betty

1-who_am_i
	- this script prints the effective username of the current user
	- you will need to execute the code below to test the script
		./1-who_am_i

2-groups
	- this script prints all the groups the current user is part of
	- you will need to execute the code below to test the script
		./2-groups

3-new_owner
	- this script will change the owner of the file hello to the user betty
	- you will need to execute the code below to test the script 
		./3-new_owner

4-empty
	- this script will create an empty file called hello
	- you will need to execute the code below to test the script
		./4-empty

5-execute
	- this script will add execute permission to the owner of the file hello
	- you will need to execute the code below to test the script
		./5-execute

6-multiple_permissions
	- this script will add execute permission to the owner and the group owner and read permission to other users to the file hello
	- you will need to execute the code below to test the script
		./6-multiple_permissions

7-everybody
	- this script will add execute permission to all the users
	- you will need to execute the code below to test the script
		./7-everybody

8-James_Bond
	- this script will add all the permission to only the others
	- you will need to execute the code below to test the script
		./8-James_Bond

9-John_Doe
	- this script will add the permissions as specified
	- you will need to execute the code below to test the script
		./9-John_Doe

10-mirror_permissions
	- this script will set mode of an hello file to be the same olleh's mode
	- you will need to execute the code below to test the script
		./10-mirror_permissions

11-directories_permissions
	- this script will set permissions to only subdirectories 
	- you will need to execute the code below to test the script
		./11-directories_permissions

12-directory_permissions
	- this script will create a directory my_dir with permissions 751
	- you will need to execute the code below to test the script
		./12-directory_permissions

13-change_group
	- this script will change group owner of hello file to school
	- you will need to execute the code below to test the script
		./13-change_group

100-change_owner_and_group
	- this script changes the owner to vincent and the goup owner to staff for all the files and directories in the working directory
	- you will need to execute the code below to test the script
		./100-change_owner_and_group

101-symbolic_link_permissions
	- this script changes the owner and group owner of _hello to vincent and staff respectively
	- you will need to execute the code below to test the script
		./101-symbolic_link_permissions

102-if_only
	- this script changes the owner of the file hello to betty only if it is owned by the user guillaume
	- you will need to execute the code below to test the script
		./102-if_only

103-Star_Wars
	- this script will play the StarWars IV episode in the terminal
	- you will need to execute the code below to test the script
		./103-Star_Wars

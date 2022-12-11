These are the list of scripts and what they do respectively

NB: Before running any scripts please execute the command below for each respective scripts
	
	chmod u+x name_of_script
		- for example: chmod u+x 1-listit
	
	0-alias
		- this script creates an alias for ls and rm *
		- you will need to execute the code below to test the script
			./0-alias

	1-hello_you
		- this script will print hello user, where user is the current Linux user
		- you will need to execute the code below to test the script
			./1-hello_you
			
	2-path
		- this script will add /action to the PATH
		- you will need to execute the code below to test the script
			source ./2-path
			echo $PATH
			
	3-paths
		- this script will count the number of directories in the PATH
		- you will need to execute the code below to test the script
			./3-paths
			
	4-global_variables
		- this script will list environment variables
		- you will need to execute the code below to test the script
			./4-global_variables
			
	5-local_variables
		- this script will list all loval variables and environment varables and functions
		- you will need to execute the code below to test the script
			./5-local_variables 
			
	6-create_local_variable
		- this script will create a new local variable (name: BEST, value: School)
		- you will need to execute the code below to test the script
			./6-create_local_variable
			
	7-create_global_variable
		- this script will create a global variable (name: BEST, value: School)
		- you will need to execute the code below to test the script
			./7-create_global_variable
			
	8-true_knowledge
		- this script will print the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE
		- you will need to execute the code below to test the script
			./8-true_knowledge
			
	9-divide_and_rule
		- this script will print the result of POWER divided by DIVIDE
		- you will need to execute the code below to test the script
			./9-divide_and_rule
			
	10-love_exponent_breath
		- this script will display the result of BREATH to the power LOVE
		- you will need to execute the code below to test the script
			./10-love_exponent_breath
			
	11-binary_to_decimal
		- this script will convert a number from base 2 to base 10
		- you will need to execute the code below to test the script
			./11-binary_to_decimal
			
	12-combinations
		- this script will print all possible combinations of two letters, except oo
		- you will need to execute the code below to test the script
			./12-combinations | tail -303 | head -10
			
	13-print_float
		- this script will print a number with two decimal places
		- you will need to execute the code below to test the script
			export NUM=0
			./13-print_float
			
	100-decimal_to_hexadecimal
		- this script will convert a number from base 10 to base 16
		- you will need to execute the code below to test the script
			export DECIMAL=16
			./100-decimal_to_hexadecimal
			
	101-rot13
		- this script will encode and decode text using the rot13 encryption
		- you will need to execute the code below to test the script
			./101-rot13 < quote
			
	102-odd
		- this script will print every other line from the input, starting with the first line
		- you will need to execute the code below to test the script
		 	\ls -1 | ./102-odd
			
	13-water_and_stir
		- this script will add the two numbers stored in the environment variables WATER and STIR and print the result
		- you will need to execute the code below to test the script
			./103-water_and_stir

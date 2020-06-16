# AutoStringToLowerCase
This project tackles the problem of case sensitive data saving and retreival by changing setter method generation code.

The setter generation is identical to the default other than that it:

	1. Checks the type of variable being set.
	2. If that variable is a String, it adds var.toLowerCase(); which will be executed whenever the variable is set.
	
This results in all String data to be forced into lowercase, making searching and debugging easier. 
	
											
											
									
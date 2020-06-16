# AutoStringToLowerCase
This project tackles the problem of case sensitive data saving and retreival by changing setter method template.

This setter template is identical to the default other than that it:

	1. Checks the type of variable being set.
	2. If that variable is a String, it adds var.toLowerCase(); to the method body.
		
This results in all String data to be forced into lowercase, making DB searching and debugging easier. 

In order to use this project copy the contents of the file named AutoToLowerCase into your IDE's template options.
											
											
									
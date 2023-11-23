### Q13. Create a folder called myteam in your home directory and change its permissions to read only for the owner.
![Q3](q3)

### 14. Log out and log in by another user.
![Q14](q14)

### 15. Try to access (by cd command) the folder (myteam)
![Q15](q15)

### 16. Using the command Line

- Change the permissions of oldpasswd file to give owner read and write permissions and for group write and execute and execute only for the others (using chmod in 2 different ways)
	![Q16](q16_a_1)

- c:
	- for files   ==> 6 == > rw- , rw- , rw-
	- for folders ==> 9 ==> rwx , rwx , rwx

### Q17. What are the minimum permission needed for:

- Copy a directory (permission for source directory and permissions for target parent directory)

	- for source directory: x
	- for target parent directory: w , x

- Copy a file (permission for source file and and permission for target parent directory)
	- for source file: r
	- for target parent directory: w , x

- Delete a file
	- for the file: ---
	- for source parent directory: w , x
	
- Change to a directory
	-  for target directory: x
	
- List a directory content (ls command)
	- r 

- View a file content (more/cat command)
	- r

- Modify a file content
	- w
 
### Q19. What is the difference between the “x” permission for a file and for a directory?
	
	- for files:
	 	   - You have theright to execute them, if they are programs(executable files).
	 	   - They cannot take x by default.
	- for directories:
	   	 - Allows you to enter the directory (cd directory).
	    	 - You can list its contents (cd -l) if you you have r access. 



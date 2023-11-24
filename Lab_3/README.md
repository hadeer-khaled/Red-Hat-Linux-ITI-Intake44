### 1. Using vi write your CV in the file mycv. Your CV should include your name, age, school,
college, experience,...


### 2. Open mycv file using vi command then: Without using arrows state how to:
	a. Move the cursor down one line at time.
	b. Move the cursor up one line at time.
	c. Search for word age
	d. Step to line 5 (assuming that you are in line 1 and file is more than 5 lines).
	e. Delete the line you are on and line 5.
	f. How to step to the end of line and change to writing mode in one-step.

### 3. List the available shells in your system.
   
![q3](q3)

### 4. List the environment variables in your current shell.
   
![q4](q4)

### 5. List all of the environment variables for the bash shell.
	
 	- step 1: Write man bahsh in the terminla
	
 	- step 2: serch for the envroiment varialble
	
  ![q5](q5_3)
	
### 6. What are the commands that list the value of a specific variable?
	- echo $VARIABLE_NAME

### 7. Display your current shell name.
![q7](q7)

### 8. State the initialization files of: sh, ksh, bash.
		1.sh (Bourne Shell):	
		    - System-wide initialization file: /etc/profile
      
		    - User-specific initialization file: ~/.profile
		
		2.ksh (KornShell):
		    - System-wide initialization file: /etc/profile
      
		    - User-specific initialization file: ~/.profile
      
		    - Additional user-specific initialization file for ksh: ~/.kshrc
		
		3.bash (Bourne Again Shell):
			-  System-wide configuration files:
				- /etc/profile
    
				- /etc/bashrc (for interactive non-login shells)
    
			- Individual user configuration files:
				- ~/.bash_profile, ~/.bash_login, or ~/.profile 
    				(Bash looks for these in the order listed and executes the first one found)
	
				- ~/.bashrc (for interactive non-login shells)

### 9. Edit in your profile to display date at login and change your prompt permanently.

### 10. Execute the following command :
	- echo \ then press enter, What is the purpose of \ ?
 		The backslash (\) will scape the newline character that I get when I press Enter.
   		It is indication that the command is not yet complete.
 
	- Notice the prompt ”>” what is that? 
 		It indicate that the shell is expecting more input to finish the command.
 
 	- how can you change it from “>” to “:”.
  		export PS1=":"

### 11. Create a Bash shell alias named ls for the “ls –l” command
	- Terminal level
 
  ![q11](q11_terminal)
 
	- User level
	   - step 1: open ~/.bashrc file
	   - step 2: write alias="ls -l"
	


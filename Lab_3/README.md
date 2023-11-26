### 1. Using vi write your CV in the file mycv. Your CV should include your name, age, school, college, experience,...

![q1](q1)

### 2. Open mycv file using vi command then: Without using arrows state how to:
-  Move the cursor down one line at time.
    - Press ` j ` 
-  Move the cursor up one line at time.
    - Press `k`
-  Search for word age.
    - Type `/age` and press `Enter`
-  Step to line 5 (assuming that you are in line 1 and file is more than 5 lines).
    - Type `5G` and press `Enter`   
-  Delete the line you are on and line 5.
    - Type `dd`, `:5d`  
-  How to step to the end of line and change to writing mode in one-step.
    - Type `A`

### 3. List the available shells in your system.
   
![q3](q3)

### 4. List the environment variables in your current shell.
   
![q4](q4)

### 5. List all of the environment variables for the bash shell.
	
- step 1: Write _man bahsh_ in the terminal.

- step 2: serch for the envroiment variables.
	
  ![q5](q5_3)
	
### 6. What are the commands that list the value of a specific variable?
	- echo $VARIABLE_NAME

### 7. Display your current shell name.
![q7](q7)

### 8. State the initialization files of: sh, ksh, bash.
1. sh (Bourne Shell):	
    - System-wide initialization file: /etc/profile

    - User-specific initialization file: ~/.profile

2. ksh (KornShell):
    - System-wide initialization file: /etc/profile

    - User-specific initialization file: ~/.profile

    - Additional user-specific initialization file for ksh: ~/.kshrc

3. bash (Bourne Again Shell):
    -  System-wide configuration files:
		- /etc/profile
	
		- /etc/bashrc (for interactive non-login shells)
	
    - Individual user configuration files:
		- ~/.bash_profile, ~/.bash_login, or ~/.profile 
		(Bash looks for these in the order listed and executes the first one found)
	
		- ~/.bashrc (for interactive non-login shells)

### 9. Edit in your profile to display date at login and change your prompt permanently.

### 10. Execute the following command :
-  echo \ then press enter, What is the purpose of \ ? 

	- The backslash (\) will scape the newline character that I get when I press Enter.
	- It is indication that the command is not yet complete.

- Nottice the prompt ”>” what is that
	- It indicate that the shell is expecting more input to finish the command.

- How can you change it from “>” to “:”
	- export PS2=":"

### 11. Create a Bash shell alias named ls for the “ls –l” command

- Terminal level
 
  ![q11](q11_terminal)
 
- User level
	- step 1: open   _~/.bashrc_  file
	- step 2: write  _alias="ls -l"_
	

# Lab 1 

### 2. What is the difference between _**cat**_ and _**more**_  command?
-  Cat
   -  Used for concatenating and displaying the entire contents of one or more files.
   -  It prints the entire file to the terminal in one go, which is useful for small files.

- More
   -  used for displaying the contents of a file page by page. It allows you to navigate through the file one screen at a time.
   -  You can use the spacebar to move forward, and the q key to exit

### 3. What is the difference between _**rm**_ and _**rmdir**_ using man?
- rm remove file.
- rm -r removw folder empty files or not.
- mkdir remove empty files only.

### 4. Create the following hierarchy under your home directory:
           dir1                 docs
            / \                   |
           /   \                  |
          /     \                 |
         /       \               mycv
       dir11     dir12 
         |
         |
       file1
  
  
![Q4](q4)

  - a. Remove dir11 in one-step. What did you notice? And how did you overcome that?
    
  ![Q4_a](q4_a)
  
  - b. Then remove dir12 using _rmdir –p_ command. State what happened to the hierarchy (Note: you are in your home directory).
    
  ![Q4_b](q4_b)
  
  - c. The output of the command pwd was _/home/user_. Write the absolute and relative path for the file mycv
      - Absolute path: ~/dir1/docs/mycv
      - Relative Path: ./dir1/docs/mycv
  
### 5. Copy the _/etc/passwd_ file to your home directory making its name is mypasswd.
![Q1](q5)

### 6. Rename this new file to be oldpasswd.
![Q6](q6)

### 7. You are in _/usr/bin_, list four ways to go to your home directory
![Q7](q7)

### 8. List Linux commands in _/usr/bin_ that start with letter w
![Q8](q8)

### 9. Display the first 4 lines of _/etc/passwd_
![Q9](q9)

### 10. Display the last 7 lines of _/etc/passwd_
![Q10](q10)

### 11. Display the man pages of passwd the command and the file sequentially in one command.
![Q11](q11)


### 12. Display the man page of the passwd file.
![Q12](q12)


### 13. Display a list of all the commands that contain the keyword passwd in their man page.
![Q13](q13)

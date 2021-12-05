# SpringCIS-5755-2021

### Group Members
Mani Kumar Goli,
Mounika Penki


### GitHub link:: 
https://github.com/golimani/SpringCIS-5755-2021.git 
### Group Activity:  
### Planning(30 mins): 
We started discussion on creating a very simple application by using flask. We planned to create a simple html page to accept age as input and display the age in Cloud9 IDE and integrate the versions with github.  
### Approach(3 hrs): 
To design the application we need the python flask framework and basic HTML code and also Github for repository version controlling. 
### Project Introduction:  
The application is a basic form in Flask that will take input from the user  and return the output. This application takes the input number and displays the output as Age.

### Major Steps::

---------------------------------------------------
Github and Cloud9 setup using Personal Access Token:
----------------------------------------------------- 
1. Login Github and Create a repository
2. get familiar with account profile --> settings -->Developer Settings -->Personal Access Tokens 
3. Click "Generate New Token" 
   a. Provide a Note such as "CIS5755"
   b. Select Expiration Date
   c. Select scopes
4. Click "Generate token", copy and paste the token in a temporary place
5. Create a new cloud9 environment
6. Delete the README.md file
7. git config --global credential.helper store
8. Go to Github and copy the repository URL
9. Go to Cloud9 terminal and clone the repository
  a. Type: git clone + repository URL
  b. enter your github username
  c. Copy and paste the token for password
10. Change directory to the new folder
11. Create a project directory (e.g. mkdir Chapter-1)
12. Change to the new directory
13. Create python envionrment: python3 -m venv env
14. To activate the envionrment: source env/bin/activate
15. Create a python file named ex1-print.py
16. Edit the python file
  a. Open the file
  b. Enter a line of code
  c. Run the file
17. While keeping the current terminal window for project,  open a new terminal for git to manage the source code) 

18. git add --all
19. git status
20. git commit -m "Py Flask example"
21. git push
  a. github username:
  b. password: copy and paste the account access token
22. check the changes by using: git log
23. Go to Github repository to check the changes
24. Go to Cloud9 and create a second python file: SimpleForm.py
25. Edit the file by copy/paste the basic Flask code
26. Save and Run the file
27. In the terminal, install Flask package (library): python3 -m pip install flask
28. In the terminal, run the file: python3 ex2-flask.py
29. To view the app, go to Tools menu, select Preview --> Preview Running App
30. To stop the service, press Ctrl + C
31. To add dependency control file requirements.txt using command : pip freeze > requirements.txt
32. In the git terminal, enter command step 17-21
   a. change commit comment to "First Flask example"

33. Create an instruction markdown file for Chapter 1
   a. Edit the file by copy/paste this lab instructions
   b. Add basic markdown styles
   c. Save the file
34. In the git terminal, enter command step 17-21
   a. change commit comment to "First Instruction File"

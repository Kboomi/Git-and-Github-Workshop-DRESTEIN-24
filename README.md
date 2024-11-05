# Git-and-Github-Workshop-DRESTEIN-24<br>
NAME:  K.BOOMIKA <br>
REGISTER NUMBER : 212222060029<br>
DEPARTMENT :  ECE<br>
YEAR :  III<br>
1. Setup and Initialize:  - What command do you use to create a new directory named `git-workshop` and navigate into it?  <br>
ANSWER: mkdir git-workshop 
                  cd git-workshop <br>
 
2. Initialize a Git Repository:  - What command initializes a Git repository in your directory?  <br>
ANSWER: git init <br>
 
3. Create and Modify Files:  - How do you create a new  ile named `hello.txt` and add the content 'Hello, Git <br>
Workshop!' to it using a single command?<br>  
ANSWER: echo "Hello, Git Workshop" > hello.txt <br>
 
4. Check the Status of Your Repository:  - What command displays the status of your repository?  <br>
ANSWER: git status <br>
 
5. Stage and Commit Changes:  - What command stages the  ile `hello.txt`?   <br>
ANSWER: git add hello.txt <br>
 - What command commits the staged  ile with the message 'Add hello.txt with <br>
welcome message'?  <br>
ANSWER: git commit -m "Add hello.txt with welcome message" <br>
 
6. Branching:  - What command creates a new branch named `update-content`?  <br>
ANSWER: git branch update-content <br>
 -How do you switch to the `update-content` branch?  <br>
ANSWER: git checkout update-content <br>
 
7. Make Changes on the Branch:  - What command would you use to append the text 'This is a simple Git assignment.' <br>
to `hello.txt`?  <br>
ANSWER: echo "This is a simple Git assignment" >> hello.txt <br>
 - What command stages and commits the changes with the message 'Update hello.txt <br>
with additional message'?  <br>
ANSWER: git add hello.txt git commit -m "Update hello.txt with addi onal message" <br>
 
8. Merge Changes:  - What command switches you back to the `main` branch? <br> 
ANSWER: git checkout main - How do you merge the `update-content` branch into `main`?  <br>
ANSWER: git merge update-content<br> 
 
9. View Commit History:  - What command shows the commit history?  <br>
ANSWER: git log <br>
 
10. Undo and Reset (Practice Safely):  - If you make a change to `hello.txt` that you want to revert before committing, 
what command would you use?  <br>
ANSWER: git checkout -- hello.txt - How can you reset your branch to a previous commit (optional, for advanced 
practice)?  <br>
ANSWER: git reset --hard <commit-hash><br> 
 
11.Push to a Remote Repository (Optional):  <br>
 - What command adds a remote repository named `origin`?  <br>
ANSWER: git remote add origin <repository-url> <br>
 
12.What command pushes your local `main` branch to the remote repository? 
 
ANSWER: git push origin main

# Exercise 1: Creating a new project

## A. Create a new project on GitHub 
(lets call it my-first-project) 
The new project will have a URL: https://github.com/your-user-name/my-first-project.git

## B. Create a local project 
1. Create a directory in your computer where you will write the code of the project. For example in Desktop/my-first-project, and cd into this directory.  

2. Activate git in the new directory
```git init```  

3. Connect the new directory to the GitHub project:
```git remote add origin https://github.com/your-user-name/my-first-project.git```

4. Write some code, e.g. e simple Python program to print something.

5. Now add the file you created to git:

- Check which files have been changed: ```git status -s```   
- Mark files to be added in the next commit: ```git add --all```  
- Commit changes: ```git commit -m "Write a message here, explaining the purpose of the commit"```  
- Push the latest commit on GitHub: ```git push -u origin main```  




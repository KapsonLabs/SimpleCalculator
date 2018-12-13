## Simple Calculator for learning Git-Workflow ##

The Simple Calculator project is solely meant for those who want to get familiar with git workflow. Git takes some getting used to before one becomes comfortable with it. Feel free to clone or fork this repository and contribute. 

### Language Preferences ###

Python has been chosen as the preferred language because of its extreme simplicity and adaptability. Therefore all the code on this repository will be written in python.

### Core calculator Functionality ###

A simple calculator should perform the following functions
  - Addition(a+b)
  - Subtraction(a-b)
  - Division(a/b)
  - Multiplication(a*b)
  - Power(aˆb)
  - Square roots(√a)
  - Modulus Operations(a rem b)
  
 ### Extended Funtionality ###
  - Trigonometric Functions
  - Binary Conversions
  - Hexadecimal Conversions
  
 ## GIT WORKFLOW ESSENTIALS ##
  
  #### 1. GETTING STARTED ####
  
  When working in Git, or other version control systems, the concept of "saving" is a more nuanced process than saving in a     word processor or other traditional file editing applications. The traditional software expression of "saving" is synonymous   with the Git term "committing". A commit is the Git equivalent of a "save". Traditional saving should be thought of as a       file system operation that is used to overwrite an existing file or write a new file. Alternatively, Git committing is an     operation that acts upon a collection of files and directories.
  
  The commands: *git add*, *git status* and *git commit* are all used in combination to save a snapshot of a Git project's       current state.
  
  Git has an additional saving mechanism called 'the stash'. The stash is an **temporary** storage area for changes that are     not ready to be committed. The stash operates on the working directory.
  
  *git add*, *git commit*, *git stash*, *git diff*
  
  ![Simple Git Workflow](/img/git-workflow-2.jpg)
  *the image above shows a simple git workflow, follow the image to get a better understanding of the commands explained below*
  
  #### git add and git commit ####
  The *git add* command adds a change in the working directory to the staging area. It tells Git that you want to include updates to a particular file in the next commit. However changes are not actually recorded until you run *git commit*.
        
  In conjunction with these commands, you'll also need git status to view the state of the working directory and the             staging area.
        
  ##### Examples ######
  Stage all changes in <file> for the next commit.
  
    git add <file name>
    
  Stage all changes in <directory> for the next commit.
  
    git add <directory name>
    
  Stage all files inside the initalized git repository. This is by far the most used *git add* convention.
  
    git add .
 
  Unstages all files that were staged with the *git add* command
 
    git reset
    
  Commit a snapshot of the staged files to the local repository. 
  
    git commit -m 'Commit Comment'

  Examine the current state of the local repository.
    
    git status
  
 #### 2. COLLABORATING ####
   *git remote*, *git fetch*, *git pull*, *git push* 


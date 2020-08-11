# MySite
This repo was created to practice git commands

Install git from here on your windows pc :  https://gitforwindows.org/

Complete the installation procedure.

Go to Git Bash:
  
  type Git in your start menu and select 'Git Bash'.

Git commands:
  
  Initial Git set up:
    
   First set your username and email using the following commands:
      
      git config --global user.name "username"
      git config --global user.email "email address"
    
  Setting up a Github account
    
   Create a github account if you don't have one already : https://github.com/
  
  Creating a new remote repository:
    
   Login to your git hub account and create a new repository.(click on plus to the right top on the page and choose 'New Repository'
   
   Copy the url of your repo (on your screen click on the green button which says 'code' and copy the url there) and note it we will use this in a later step.

  Pushing to GitHub:
    
   Preparing to use Git:
      
      mkdir <Directory name>  (replace <Directory name> with your directories name eg: mkdir NetworksProject)
      cd <Directory name> (replace <Directory name> with your directories name eg: cd NetworksProject)
      
      git init
      (do not use cntrl + v to paste anything in git bash instead do right click -> paste)
      git remote add origin <URL> (<URL> is the url of your repo that you copied) 
      touch index.html (touch command is used to create an empty file replace index.html with your file name)
      git add index.html (add the created file to ur repo)
      git commit -m "Create index.html" (commit act like comments and help us track the changes that are made)
      git push origin master (pushing the changes to the repo)
      git pull origin master (pulling the changes from the repo)
      (it is recommended that you always make a "pull" request before you make a "push" request.)
      
Now Go to your github account and refresh the page the changes you made in your gitbash will be reflected here!
      

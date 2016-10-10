#What is a branch  
    A branch in git is a way of storing commits in independent lines on the development tree. The default name for a branch is master. You can think of branches being a way of having a new working directory, staging area or project history.  
    
#Why use branches  
    In git branches are used as part of everyday development process. When you want to add a new feature to the project you create a new branch to keep the changes on seperate from the main project in case there is any error made it doesn't inpact the main code base for the project. Branching also gives you the chance to clean up your feature's history before merging it into the main branch  
#Some commands  

`git checkout -b przemyslaw_byrdy` creates a new branch  
`git branch -d new_form` deletes a branch  
`git checkout master` selects a new branch  

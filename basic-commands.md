Check Current Git Version

    git --version

To set configuration for local profile : 

     git config --global user.name <user_name>

     git config --global user.email <user_email_address>

To see list of global configurations : 

    git config --global --list
    
To make a directory into a git repository : 
  
    git init
    
To check status of repository

    git status
    
To bring a file to staging area and start tracking changes : 
  
    git add <file_name>
    git add . (brings all files into staging area)
    
To commit the changes : 

    git commit -m <commit_message>
   
Display the log of all commits 

    git log
  
    git log --oneline
    
To list all branches 

    git branch
    
To create a new branch 
  
    git branch <branch_name>
    
To checkout to another branch 

    git checkout <branch_name>
    
To create and checkout to a new branch 

    git checkout -b <branch_name>
    
To merge changs from source branch to current branch

    git merge <source_branch_name>
    
    git rebase <source_branch_name>    // park the changes in current branch , apply changes from source and put the parked changes back on top 
    
To delete a branch 
    
    git branch -d <branch_name>  // Safe Delete, throws a warning when changes are not merged
    
    git branch -D <branch_name>  // Hard Delete, No warning to users
  
To create a tag

    git tag <version> // e.g. git tag v1.0.0
    
To list all tags

    git tag
    
To Delete a tag

    git tag -d <version>
    


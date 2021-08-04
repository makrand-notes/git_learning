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
  
  

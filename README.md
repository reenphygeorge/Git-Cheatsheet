## Git Commands ##

### Notes ###
    
* Open the required directory in any Unix terminal (Linux/ MacOS/ Git Bash).
* alias name: eg: origin
* branch: eg: master

### Configuring Git ###

* Configuring username globally

      git config --global user.name "<username>"

* Configuring email globally

      git config --global user.email "<email>"

### Commands ###

 * Locally initialize a git repository

       git init
       
 * To add remote repository

        git remote add <alias name> <git repo url> 
       
 * Add all files to staging area
 
        git add -A
        
 * Add specific files to staging area
 
        git add <filename>
        
 * Commit files
        
        git commit -m "<commit message>"
        
  * Push Files to github
  
        git push <alias name> <branch>
        
  * Pull: To sync remote repo with github repo
  
        git pull <alias name>
      
  * Clone a git repository
  
        git clone <git repo url>

  * To know the current status of a local git repository
  
        git status
  
  * For more arguments
  
        git help

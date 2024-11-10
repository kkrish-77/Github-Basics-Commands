The Basics of Git

# to download git into your system

    sudo apt install git

#TO initialize git 

    git init 

#To configure your username and gmail

    git congfig -global user.name "User name "

    git config --global user.gmail "gmail "

#To check the verison of git

    git --version

#TO add the file into the git and change its state to untracked to staged

    git add <file_name>

#To check the status of the file

    git status 

#To change it to from staged to untracked

     git rm --cached <file_name>

#To change the state of the file to untracked to tracked

    git commit -m <file_name>

#To restore the file if it has been deleted
    
     git restore <file_name>

#To set Github repository

     git remote set-url origin <Link_of_repository>

#To push the contents to repository

    git push -u origin main

    
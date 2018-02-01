Git
A version control system It is a way for us to work with different versions of our code
so that we can save different features and make notes as we progress and have different 
version as we move forward or backward

Git is a technology and github is a website
Git init: i am gonna use in this folder hahahaha, usually one repository for one project
          ls -a show hidden .git file
========================================================================================================
Git status: type git status to see ur current status
            how many files u have 
========================================================================================================
Git add: tell the git to add the file
         git add <fileName> 
         git add .      this add all modified files  git commit -m "all files which add . are commit"
========================================================================================================
Git commit: checkpoints first add then commit
        git commit -m "message"
========================================================================================================
Git log: check your commits
       git log: copy unique commit hash 
to end type q       
========================================================================================================
Git checkout: 
       git checkout <uniqueHastCommit>
       after this we are no longer master branch

       go back old version and start using: git revert --no-commit <id>..HEAD
       go back old version and come back to master: git checkout master
========================================================================================================
Git Uploading: uploading files to ur respository
       git remote add origin <url>.git
       git remote -v: to check origin added to the remote
       git push -u origin master: upload code
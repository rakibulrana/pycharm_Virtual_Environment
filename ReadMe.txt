1. Create a folder in your local machine
2. In pycharm terminal use following command to careate virtualEnvironment Folder
        py -m venv VirtualEnvironmentFolder(name of your file)
3. Using command navigate to the new created 'VirgualEnvironmentFolder'
        cd VirgualEnvironmentFolder
4. In newly created VirgualEnvironmentFolder find and run 'Script file' 
        Cd Scripts 
5. activate (write actiavte and enter)
6. cd .. (to comeback to the root folder)

N: B: at some point either (essentially in between number 3&4 or at the end) we have to active the virtualenvironment from the file menu.
              file/setting/project Interpreter/ if you find the python for your root folder then click Ok, 
              if not found then "SHOW ALL" from "Show all" select the python version with virtual Environment
              otherwise click on 'plus' button and from OK you will find automatically python existing version for your root folder.

## install packages 
1. create a file in the root folder ex: requirements.txt
2. wirte all the package names sequentially (using enter for new line)
3. pip install -r requirements.txt


########################          git krank
1. Double click Dev brnach (bikash branch)
2. pull all 
3. come back to Ran Branch 
4. click again Dev/Bkash branch (single click)
5. Merge Dev/Bikash ino Rana_branch

        ############## 
        -       view changes
        -       stage all changes 
   #################################### git ##################dustin
   
   Git commands from Dustin to push your dev code, pull the recent cheanges from the DEV and finally push again to make everything up to date
1. Go to the git repo and create a new repo. give the name
2. check the README option to initialize a file with a default ReadMe file.
3. create a local version of the git repo
4. git clone [http link of the git we've created on the web]
5. change something on the ReadME file and prepare to push that to the master branch
5. git add .
6. git commit -m "Comment of your changes"
7. git push 
8. or git push origin master
__________________  
- git branch
- git commit 
- git add -A .
- git commit -m 'Type Your commit Text'
- git push
 
- git checkout dev
	(Switched to branch dev)
- git pull origin dev
- git checkout inti_test
	(Switch to branch 'inti_test')
- git merge dev
	(Now I was in 'inti_test' branch, and the 'dev' branch is merging with the 'inti_test' branch)

- git add -A .
- git commit -m 'merge with dev'
- git push

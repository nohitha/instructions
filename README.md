# instructions to push to git
* to check git is installed or not: git
* to check status: git status
* Go to the project folder which you want to push to git in cmd and create an empty repositry: git init
* To add everything in the folder: git add.
* To add a particular file or folder: git add app/filename
* After adding check git status: git status
* Then add a message what changes have been done to that file/folder by commit command: git commit -m "first commit"
* Copy http or ssh url which is present in code drop down option and paste it in this command: git remote add origin "paste ur url"
* Finally push your file to mater branch by this commad: git push -u origin master
# instructions to pull from git to desired folder
* Go to desired folder in which you want to place the pulled code by cmd: cd directory or folder
* Create a new empty repositry in that folder: git init
* Then add origin copy http url of that file from github and paste in this command: git remote add origin paste url
* git pull origin master

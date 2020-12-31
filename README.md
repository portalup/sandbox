Git Notes
*Use "git status" to see current details
*git checkout [branch] switches branches

#Connect Repo
1) Create Repo with README.MD
2) Connect to files on PC in IDE terminal
- Go to file location and open Git Bash
- Enter in the command line >git init
- Enter in the command line >git remote add origin [REPO-URL]
- Enter in the command line >git add .
- Enter in the command line >git commit -m "details"
- Enter in the command line >git push origin master
- It will pull files in master branch

#Update code to Github
1) Changes are made in IDE and saved
2) In terminal >git status
- Enter in the command line >git add .
- Enter in the command line >git commit -m"details"
- Enter in the command line >git push origin master
  -master may change based on branch, sometimes "main"

#Pull code on Git with PC - First time
1) In terminal >git clone [REPO-URL]

#Pull code and files on Git to PC
1) In terminal >git pull origin master


#Delete file on Github
1) Delete file from connected location
2) In terminal >git status
- Enter in the command line >git add .
- Enter in the command line >git commit -m"details"
- Enter in the command line >git push origin master


#################################################################

#Sync files to mobile/tablet devices
1) Merge code from GitHub to device
- Click Pull and chose Branch and Origin
- Code will now come from Git to device


2) Add code to Github
- Once you have finished coding, click Commit All
- Add details to Commit and click on Push
- Choose Branch and Origin
- Code is now on GitHub


3) Add file to Github
- Once you have finished coding the new file, click Commit All
- Add details to Commit and click on Push
- Choose Branch and Origin
- The file is now on GitHub

4) Remove file
- Delete file on IDE
- Commit & Push


#################################################################

#Setup code to GitPod
1) Create Repo and connect to GitPod
2) Setup basic walkthrough in GitPod

#Update file on Github
1) In terminal >git status
- Enter in the command line >git add .
- Enter in the command line >git commit -m"details"
- Enter in the command line >git push


#################################################################

#SSH
1) Create SSH in PC if permission error appears
- Enter in the command line >ssh-keygen
- You may need to remove previous one in Drive
2) Enter in passcode
3) Find id-rsa file in Drive & copy ssh-key
4) Add key to GitHub SSH settings


#################################################################
#Details of the project and todo notes

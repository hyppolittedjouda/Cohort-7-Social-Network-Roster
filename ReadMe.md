#Read Me

(Note that all command lines and addresses will be enclosed in >< so as to grant more
clarity, the commands themselves will not need these unless they are doubled (>><<))

My process for creating this file and pushing it to GitHub:

-Started Git Bash and used command >pwd< to verify the current directory

-Used >cd /c/Users/justi/Documents< to change to my local documents directory

-Created a new Repository using >git init Cohort7-Network_Roster<

-Changed the current directory to the new Repository using
>cd /c/Users/justi/Documents/Cohort7-Network_Roster<

-Created a Read Me using >touch ReadMe.md<

-Opened and edited the Read Me using >nano ReadMe.md<

-Exited and saved the Read Me by pressing >Ctrl & x< to exit nano and
typing >y< and then >Enter< to confirm changes (For brevity I will not be
listing the full Nano steps in the future)

-Created and edited Social List using >touch Social_Account_Lists.md<

-Used >git status< to verify which files had been created/modified

-Started tracking all modified files to commit the changes using >git add . <

-Committed all the files using >git commit . <

-Checked the current remote server for the directory using >git remote -v< 
Verified there was no remote server assigned

-Assigned the remote server using
>git remote add origin https://github.com/Justin-Hughes/Cohort-7-Social-Network-Roster.git<

-Pushed the directory to the GitHub repository using >git push -u origin master<

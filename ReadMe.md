# Read Me

My process for creating this file and pushing it to GitHub:

* Started Git Bash and verified the current directory
```bash
$ pwd
```

* Changed to my local documents directory:
```bash
$ cd /c/Users/justi/Documents
```

* Created a new Repository using
```bash
$ git init Cohort7-Network_Roster
```

* Changed the current directory to the new Repository using
```bash
$ cd /c/Users/justi/Documents/Cohort7-Network_Roster
```

* Created a Read Me using
```bash
$ touch ReadMe.md
```

* Opened and edited the Read Me using
```bash
$ nano ReadMe.md
```

* Exited and saved the Read Me by pressing ```Ctrl & x``` to exit nano and
typing ```y``` and then ```Enter``` to confirm changes (For brevity I will not be
listing the full Nano steps in the future)

* Created and edited Social List using
```bash
$ touch Social_Account_Lists.md
```

* Used ```git status``` to verify which files had been created/modified

* Started tracking all modified files to commit the changes using ```$ git add . ```

* Committed all the files using ```$ git commit . ```

* Checked the current remote server for the directory using ```$ git remote -v```
Verified there was no remote server assigned.

* Assigned the remote server using
```bash
$ git remote add origin https://github.com/Justin-Hughes/Cohort-7-Social-Network-Roster.git
```

* Pushed the directory to the GitHub repository using
```bash
$ git push -u origin master
```

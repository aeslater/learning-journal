[Home](/README.md)]

### Learning Journal Notes
# Revisions and the Cloud
---

## Git (version control) vs. Github (online code storage)

Git is a version control system. 
Commits save the file with a new version; you add a change description each time.
'Head' means the latest saved version.

Github is an online place to store code and collaborate with others
It uses git version control system.

A repository (repo) is a collection of files on GitHub or on computer.

## Cloning Github Repository
To clone an existing Github repository to a local working directory, first create the directory you want to use and make that your working directory. Then copy the repository's URL. Use the clone command to copy the existing Git repository `git clone https://github.com/example`. Now you can work in Visual Studio or other software to edit the files and push back to your remote repository, as described below.

## Add Commit Push (A-C-P)

### Add

When creating new files or modifying existing ones, the file state is modified meaning the file has been changed but not committed. When ready, track the files in your working directory using command `git add filename` or `git add *` to track all files in the repository. Now they are in the index, the area used for staging.

### Commit

After staging one or more files, the next step is to commit changes, which commits a snapshot of all modifications to tracked files in the working directory. In this step you should describe the changes you made to keep a clean history. Use command `git commit -m 'description of change'` or `git commit -a` to commit all changes to tracked files in the working directory.

### Push

The last step is to push the changes to the remote repository using command `git push origin master`; this command pushes changes from the local 'master' branch to the remote repository named 'origin'.

### Status
At any time to see the status of files in the repository vs. the master, use command `git status`. It displays number of files that require action or states that your branch is up to date.

### Reference
This is a summary from [Git Tutorial: A Comprehensive Guide](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#7_2).
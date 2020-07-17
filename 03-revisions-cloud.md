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

## Add Commit Push (A-C-P)

### Add

The first step is to add files or make changes to existing files. When ready, move files to staging area using command `git add`.

### Commit

The next step is to commit changes. In this step you should describe the changes you made to keep a clean history. Use command `git commit -m 'description of change'`.

### Push

The last step is to push the changes to the master using command `git push origin master`.

### Status
At any time to see the status of files in the repository vs. the master, use command `git status`.
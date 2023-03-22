# Git Tutorial

[Git Tutorial: A Comprehensive Guide](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

## Version Control

a LVC (local version control) is a database on your hard disk that stores changes to files

CVCS or Centralized Version Control System is similar but the file version can be accesed by various clients this gives everyone on the project more knowledge of team members changes to the files

Snapshots

Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

Local Operations

Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.

Tracking Changes

Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.

Loss of Data

Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.

Controlled by terminal

1.What is Version Control?

-A local database for soting changes to files

2.What is cloning in Git?

-When you make a local copy of existing Git repository

3.What is the command to track and stage files?

-git add file name or git add .

4.What is the command to take a snapshot of your changed files?

-git commit -m “made change x,y,z”

5.What is the command to send your changed files to Github?

-git push origin main

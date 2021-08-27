# what is Git? 
Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.
# Local Operations

Git mostly relies on local operations because most necessary information can be found in local resources. 
This allows for process expediency because a project’s history resides on the local disk,
 eliminating the need to fetch history information from the server, 
and allowing one to continue work on a project even when not online or on a VPN.

# States

Files in Git can reside in three main states: committed, modified and staged.

 **Committed**

Data is securely stored in a local database

 **Modified**

File has been changed but not committed to the database

# you can Download Git for : 
1-[Mac OS X](http://git-scm.com/download/mac)   
2-[Windows](http://windows.github.com)  
3-[Linux](http://git-scm.com/download/linux)  




 # Workflow
The local Git repository has three components:
1.Working Directory: The actual files reside here.
2.Index: The area used for staging
3.Head: Points to the most recent commit

![Repository Structure](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)


# The Life Cycle of File Status
1.After you edit a file, Git flags it as modified because of changes made after the previous commit.
2.You stage the modified file.
3.Then, you commit staged changes.

![The Life Cycle of File Status](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)


Saving Changes
All files in a checked out (or working) copy of a project file are either in a tracked or untracked state.

  **Tracked**

Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.

**Untracked**

Untracked files were not in the last snapshot and do not currently reside in the staging area.

*After cloning a repository, files have tracked status and are unmodified because they have been checked out but not edited.

















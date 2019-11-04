Version control is a system to track and save modifications of various versions of a file. With this ability, we can revert back to the previous version. Think of it as when updating your OS system. When the newest version failed, we would revert back to the last known backup. There are 3 types of VC.

### Local Version

* Local Version Control has a database that is saved on a local computer.

### Centralized Version Control

* CVCS (Centralized Version Control System) was invented to scale up the Local VCS. With CVCS, teams can collaborate by working on a centralized file saved in a centralized database. Various clients can access this centralized database.


### Distributed Version Control

* DVCS (Distributed Version Control System) fixes a crucial vulnerability of a CVS. With CVS, the file is served in a centralized server. It has a single point of failure. If this centralized database goes down, files saved in that database is gone. DVCS allows host to create mirrored repo.

### Git

What is git? Git is a DVCS. It takes a snapchat of changed version of the file when commiting. Commit is an important keyword in Git. When you do a commit, it means you are saving a snapchat of the changed made and  stores a reference to it. Git also tracks every changes made to a file or directory.

There are three main states where file can reside in Git;
* Commited
    * Changes made is securely saved in a database.
* Modified
    * File has been changed, but not saved to the database.
* Staged
    * Flagged a changed in file to be commited in the next snapshot.


![A workflow of how Git works](img/git.png)
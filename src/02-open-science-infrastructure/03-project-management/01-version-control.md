# Version Control

Version control is a system that keeps track of all changes made to a file or group of files in the history of a project. It allows users to take snapshots of their project, so that older versions of the project can be referenced as needed. It also allows multiple users to access, make changes, and merge those changes to a single project.

There are two major types of version control: centralized and distributed.

## Centralized version control
In centralized version control systems (CVCS), there is one central server that holds the entire project and developers download a single file at a time to make changes. Version changes and conflicts are managed through file locking, where only one user can change a file at a time, or merging, where conflicts are mostly manually resolved. Examples of CVCS are Revision Control System (RCS), Concurrent Versions System (CVS), and Subversion (SVN).
- Advantages of CVCS:
  - Intuitive to use
  - Relatively quick start-up for new users
- Drawbacks of CVCS:
  - Only one backup of the whole project exists 
  - Difficult to push conflicting changes
  - Inefficient merging strategy can lead to data loss and errors
  - Slow project development with teams

## Distributed version control
In distributed version control systems (DVCS), each user has a copy of the entire project, including its full history. Therefore multiple copies of the whole project exist. Version changes and conflicts are resolved through merging, which DVCS are generally good at doing automatically. Popular examples of DVCS are Git and Mercurial (Hg).
- Advantages of DVCS:
  - Multiple backups
  - Users can make and push changes freely (no file locking)
  - Effective automatic merging strategy
  - Well-documented infrastructure
- Drawbacks of DVCS:
  - Complicated, steep learning curve

## Additional resources
Helpful description of Version Control in [Feist et al. CAADRIA. 2017](http://papers.cumincad.org/data/works/att/caadria2017_132.pdf)

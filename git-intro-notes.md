# Understanding git

**Version Control**

Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. through version 
control, you can revert to a previous version, track modifications and who modified it, and compare those changes. You can easily correct
mistakes by using by using a Version Control System (VCS).

**Types of Version Control Systems**

1. Local Version Control - Is a single database on your harddrive that stores changes to files.
1. Centralized Version Control (CVCS) - To be able to colaborate with a team, use a CVS. This uses a centralized database which enables      all users on the team to access the file.
1. Distributed Version Control (DVCS) - This type of VCS allows clients to create mirrored repos. These data backups can be easily be 
   placed on the server to replace any lost information, in case the server ever goes down. This allows developers to collaborate in 
   various ways.
   
   **Git**
   
   Git takes snapshots of changes to files, so it's easy to see what has been done. Most Git work is done locally. All changes are tracked
   by Git. Git makes it difficult to lose data by taking snapshots of all changes.
   
   **Git States**
   
   - Committed - Data is securely stored in a local database.
   - Modified - File has been changed but not committed to the database.
   - Staged - The file has been flagged for changes to be committed in the next snapshot.
   
   

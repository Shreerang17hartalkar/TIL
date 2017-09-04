##Git States
-->Git has three main states that your files can reside in: Committed,modified and staged.Committed means that the data is safely stored in your local database.Modified means you have changed the file but have not committed in your database.Staged means you have marked a modified file in its current version to go into your next commit snapshot.This leads
us to the three main sections of a git project:Git directory,working directory and the staging area.the **Git Directory** is where Git stores the metadata and object database of your project.This is the *most important* part of Git and it is what is copied when you clone a repository from another computer.The **Working Directory** is a single check out of one version of the project.These files are pulled out of the compressed database in the git directory and placed on the disk for you to use or modify.The **Staging Area** is a file,generally contained in your git directory,that stores information about what will go into your next commit.

The basic **Workflow** goes something like this:

1.You modify files in your working directory.

2.You stage the files,adding snapshots of them to your staging area.

3.You do a commit,which takes the files as they are in the staging area and stores the snapshot permanently in your Git directory.

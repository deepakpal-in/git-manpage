### Remove folders from Remote Git repositories keeping local folders 

Some time we are struggling with directories in git repositories. Below is a process to remove the unwanted folders/directories from remote git repo keeping them safe at local system.

This kind of scenarios arises when we are working with some local environments like IDE etc. and don't want to push those chanes to remote git repository server

```git rm -r --cached <directory name>```
```git commit -m "Removing  unwanted directory"```
### Replicating changes on remote repository server
###
```git push origin <your-git-branch-name>```

### 1. Clone your fork:

    git clone git@github.com:YOUR-USERNAME/YOUR-FORKED-REPO.git

### 2. Add remote from original repository in your forked repository: 

    cd into/cloned/fork-repo
    git remote add upstream git://github.com/ORIGINAL-DEV-USERNAME/REPO-YOU-FORKED-FROM.git
    git fetch upstream

### 3. Updating your fork from original repo to keep up with their changes:
    
    git merge upstream/master master

> Besides that you can also use **git pull** which will perform fetch and merge in a single step.

    git pull upstream master

### 4. Now your fork is upto date but locally only not on github. follow bellow procedure to reflect these changes on your github account. Add all files to your 	 git hub fork master branch

	git add .

### 5. commit all changes to your remote git hub fork repo

	git commit -m "your-commit-message"	

### 6. push all changes to your remote fork repo (reconfirm that your forked repo is your default configured repo under .git directory)

	git push 	

### You are UpToDate now...!!! :+1:

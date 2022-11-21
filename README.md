<h2>repository made to learn all git commands</h2>
<h4>all commands</h4>
<p>
  1.git config: This command sets the author name and email address respectively to be used with your commits.<br>
    git config –global user.name “[name]”  <br>
    git config –global user.email “[email address]”
  
  2.git init: This command is used to start a new repository.<br>
    git init [repository name]
  
  3.git clone: This command is used to obtain a repository from an existing URL.
    git clone [url]  
  
  4.git add: This command adds a file to the staging area.
    git add [file]  
  
  5.git commit: This command records or snapshots the file permanently in the version history.
    git commit -m “[ Type in the commit message]”  
  
  6.git diff: This command shows the file differences which are not yet staged.
    git diff
  -->This command shows the differences between the files in the staging area and the latest version present.
    git diff –staged 
  -->This command shows the differences between the two branches mentioned.
    git diff [first branch] [second branch]  
  
  7.git reset:This command unstages the file, but it preserves the file contents.
    git reset [file]  
  -->This command undoes all the commits after the specified commit and preserves the changes locally.
    git reset [commit]
  --> git reset –hard [commit]  This command discards all history and goes back to the specified commit.
    git reset [commit] 
  
  8.git status: this command lists all files that are to be commited.
    git status
  
  9.git rm:This command deletes the file from your working directory and stages the deletion.
    git rm [file]  
  
  10.git log: This command is used to list the version history for the current branch.
    git log
  -->This command lists version history for a file, including the renaming of files also.
    git log –follow[file]  
  
  11.git show:This command shows the metadata and content changes of the specified commit.
    git show [commitID]
  
  12.git tag: This command is used to give tags to the specified commit.
    git tag
  
  13.git branch:This command lists all the local branches in the current repository. 
    git branch  
   -->This command creates a new branch
    git branch [branch name]  
  -->This command deletes the feature branch.
    git branch -d [branch name]  

 14.git checkout: This command is used to switch from one branch to another.
    git checkout [branch name]  
-->This command creates a new branch and also switches to it.
    git checkout -b [branch name]  

15.git merge: This command merges the specified branch’s history into the current branch.
    git merge [branch name]  
  
16.git remote: This command is used to connect your local repository to the remote server.
    git remote add [variable name] [Remote Server Link]  

17.git push:This command sends the committed changes of master branch to your remote repository.
    git push [variable name] master  
-->This command sends the branch commits to your remote repository.
    git push [variable name] [branch]  
-->This command pushes all branches to your remote repository.
    git push –all [variable name]  
-->This command deletes a branch on your remote repository.
    git push [variable name] :[branch name]  

18.git pull: This command fetches and merges changes on the remote server to your working directory.
    git pull [Repository Link]  

19.git stash:This command temporarily stores all the modified tracked files.
    git stash save  
-->This command restores the most recently stashed files.
    git stash pop  
-->This command lists all stashed changesets.
    git stash list  
-->This command discards the most recently stashed changeset.
    git stash drop  
</p>




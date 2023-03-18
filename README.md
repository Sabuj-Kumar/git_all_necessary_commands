# git_all_necessary_commands
Quick Start Guides to Git Concepts(https://www.gitkraken.com/learn/git) 

Git config: 
  git config --global user.email youremail@example.com
  git config --local user.email youremail@example.com
  git config --global user.name "Your Name"
  git config --global user.password "Your Name"
  
Git add
    git add .(dot for all change add) (git add change_file_name for change only this file)
    
Git commit
    git commit -m "your commit"
    
Git push
    git push / git push origin branch name
    
Git pull
    git pull / git pull origin branch name
    git pull --all  – Fetch all remotes. 
    
Git fetch 
    fetch -all
    
Git checkout branch
    git checkout branch name
    
Git create new branch
    git checkout -b new branch name
    
Git merge
    git merge – Combine two or more development histories together. Used in combination with fetch, this will combine the fetched history from a remote branch into the     currently checked out local branch.
    git merge <branch-name> – Merge changes from one branch into the branch you currently have checked out.
    git merge --abort – Aborts the merge process and restores the project’s state to before the merge was attempted. This works as a failsafe when a conflict occurs.
    git merge --continue – Attempt to complete a merge that was stopped due to file conflicts after resolving the merge conflict.
    git merge --no-commit – Combine branch into the current branch, but do not make a new commit.
    git merge --no-ff – Creates a merge commit instead of attempting a fast-forward.
    
Git set new URl
    git remote set-url origin new.git.url/here
    
Git see origin details
    git config --list --show-origin
    
Git remove all uncommit state
    git stash
    
Git change branch name
    git branch -m old_branch_name new_branch_name
    
Git copy branch 
    git branch -c
    
Git delete branch
    git branch -D <branch-name> Delete a local Git branch with unmerged changes.
    git branch -d <branch-name> – Delete a local Git branch. This command will not work if the branch you are attempting to delete has unmerged changes.
    
Git display all branch
    git branch -r – Display a list of the remote branches in your Git repository
    
Git clone
    git clone <repository-url> – Clone a specified remote repository. See Git-SCM’s best practices for remote URL format
    git clone <repository-url> <directory-name> – Clone a repository and name the local directory.
    git clone <repository-url> --origin <name> – Clone a repository and name the remote (<name>). If you do not wish to name the remote, Git will provide the default       name origin.
    
Git show status of the origin
    git status

Git generate SSH key
    ssh-keygen -t rsa -b 4096 -C "your_email@example.com" - pest it in you git bash,(https://www.atlassian.com/git/tutorials/git-ssh)
    go to url where ssh key gerate.
    after then go to you git setting.
    then go to the SSH and GPG Keys option 
    then click new SSH key 
    after then give title off SSH key and pest it to the key block and press add SSH key
    

# git_commands
Some commands for using github on Ubuntu

-Install:
    sudo apt-get install git
- Configuring:
    git config --global user.name "username"
    git config --global user.email "email"
- Creating repo from local dir
    git init repo_name
- Creating README (in repo dir)
    gedit README
- Adding repo files to next commit (by file or all in repo dir)
    git add filename.xxx
    git add .
- See all files that will be commited on next commit
    git status
- Commiting
    git commit -m "message that will appear on commit"
- Connecting local repo dir with existing github repo
    git remote add origin https://github.com/username/repo_name.git
- Push commits
    git push origin branch_name
 - Cloning a repo
    git clone https://github.com/user name/repository name
 - Pulling from repo (assuming it's already linked)
    git pull

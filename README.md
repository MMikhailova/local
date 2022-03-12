# My notes

## Helpful Links

[Markdown](https://www.markdownguide.org/basic-syntax)  
[Git and GitHub for Beginners - Crash Course](https://youtu.be/RGOj5yH7evk)  
[Git cheatsheet](https://github.com/0nn0/git-basics-cheatsheet)  
[VS code cheatsheet](https://vscode-shortcuts.com/).   
[Terminal cheatsheet](https://github.com/0nn0/terminal-mac-cheatsheet)

## How to clone repo from GitHub to a local directory

- create a repo on GitHub
- clone-->copy repo link
- create a local folder via VS
- type in Terminal: git clone paste the link from GitHub
- cd folder name

## How to push changes to my GitHub(remote) from local directory:\*\*

- git status serves to show changes made
- git add . or git add README.md to add new files
- git commit -m "Add file and modify README" -m "Description"
- git push

## How to create SSH keys

- ssh-keygen -t rsa -b 4096 -C"YourGitHub email"
- generating public/private rsa key pair
- enter the file in which to save the key, you can change the name ex.testkey
- enter your passphrase
- to search for the key generated: ls | grep testkey
- cat testkey.pub
- copy the key from terminal and paste into GitHub
- [Generating a new SSH key and adding it to the ssh-agent](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

## How to create a local repo and push it into GitHub

- create a folder in VS Code with a file
- cd folder name
- git init
- git add .
- git commit -m"add files"
- create a new repo in GitHub and copy the SSH link
- in terminal: git remote add origin SSH link
- git remote -v (to see the remote repo connected to this repo)
- git push -u origin master (-u set up upstream)

## How to add branches

-git brach -to create a branch
-git checkout branch -to switch to a branch

-
- git branch to check which branch you are in
- checkout -b feature-"name"-"description"
- checkout serves to switch between branches
- git add name.md
- git commit -m"Update name.md"
-
- git checkout master
- git diff feature-name
- To merge locally: git merge feature-name
- To push into GitHub first: git push --set-upstream origin feature-name
  git
- Create a pull request in GitHub
- git pull (to merge into local)

.Gitignore
ls -a - to see hidden filees

## Work on a project

- To be able to pull changes you need to be a collaborator
  - Settings --> collaborators

## Terminal

Tab to finish word
cmd shift+V - paste

## Project board

Basic

## Vocabulary

Components - parts (boxes) of HTML page
Push -from local machine
Pull - accept one's code

## To pull from GitHub to local cloned repo

git pull origin main

<h1>Git Notes</h1>

<br />

<h3>Basic Commands</h3>

- git init : sets up a repo in current folder
- git add : tells git the file exists, adds to staging area, and tracks
  - --all : takes any changed/untracked files in repo and adds them to the repo and update the repo's working tree
- git clone <repo url> : allows users to obtain a local development clone of project already in central repo
    - For SSH URLs : git@HOSTNAME:USERNAME/REPONAME.git
- git status : tells status of system
- git commit : saves instance of files 
  - -m : add message to log on what you did/why
- git log : gives history of repo and commits

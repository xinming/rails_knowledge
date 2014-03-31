## Git knowledge Requirement

#### Cheatsheet
* `git init` Init git repo in local directory
* `git clone [URL]` clone remote git repo
* `git branch` list all branches
* `git branch [NEW_BRANCH_NAME]` create a new branch
* `git fetch` pull updates from all remote branches
* `git pull origin master` or `git pull [REMOTE_NAME] [BRANCH_NAME]` pull updates from one branch
* `git checkout [BRANCH_NAME]` switch to another branch
* `git status` check current status
* `git add [FILE_NAME/DIR_NAME]` stage files/dir before commit
* `git commit -m "[MESSAGE]"`
* `git push origin master/[BRANCH_NAME]` 
* `git reset HEAD [FILE_NAME/DIR_NAME]` remove files from stage
* `git diff [FILE_NAME]` check the diff for particular file

##### Workflow for important projects currently in production
* Fork Remote Repo
* Make a New Branch for the feature
* Implement feature
* Make pull Request and wait for merge by a senior developer
* **Please commit often, and separate each one of them nicely. Don't just `git add .` and pushes everything in 20 files. **

##### Example Workflow during work
* `git pull` or `git clone`
* implement feature
* `git status`
* `git add [FILE_NAME/DIR_NAME]`
* `git commit -m "[MESSAGE]"`
* `git push origin master/[BRANCH_NAME]`



<hr />
###### ~/.git_config (gives colored output config for using git)
<pre>
[user]
	name = Xinming Zhao # change to your name 
	email = x@dgm59.com # change to your email
[color]
 branch = auto
 diff = auto
 status = auto
[color "branch"]
 current = yellow reverse
 local = yellow
 remote = green
[color "diff"]
 meta = yellow bold
 frag = magenta bold
 old = red
 new = cyan
[color "status"]
 added = yellow
 changed = green
 untracked = cyan
[core]
	excludesfile = /Users/x/.gitignore_global # change to your username
	editor = /usr/bin/vim
</pre>

###### ~/.gitignore_global
<pre>

# Compiled source #
###################
*.com
*.class
*.dll
*.exe
*.o
*.so

# Packages #
############
# it's better to unpack these files and commit the raw source
# git has its own built in compression methods
*.7z
*.dmg
*.gz
*.iso
*.jar
*.rar
*.tar
*.zip

# Logs and databases #
######################
*.log
*.sql
*.sqlite

# OS generated files #
######################
.DS_Store
.DS_Store?
._*
.Spotlight-V100
.Trashes
ehthumbs.db
Thumbs.db
</pre>

<hr />
#### Other Tools
Download Gity
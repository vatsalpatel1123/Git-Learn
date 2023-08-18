🚀 Unleash the Power of Git Commands! 💻
Welcome to my GitHub profile, where I've embarked on an adventure to explore the captivating realm of Git commands. 🌌 Here, you'll find a curated collection of my discoveries, experiments, and insights into the art of Git Commands. Whether you're a newbie explorer or a seasoned command-line voyager, there's something here for you!

Creating a repository
Clone an existing repository.
$ git clone
Create an empty repository.
$ git init
Adding Local Changes
Changed files in the working directory
$ git status
Changes to track files
 $ git diff
Adding all the current changes to the next commit
$ git add .
Adding some changes to the next commit
$ git add -p
Commit all local changes in tracked files
$ git commit -a
Commit previously staged changes
$ git commit
Change the last commit
$ git commit -amend
Commit History
View all commits, starting from the latest one
$ git log
Show all the changes made in a file in a specific period
$ git log-p
Changes made by a person in a with timing
$ git blame
Branches and Tags
List all existing branches
$ git branch -av
Switch master branch
$ git checkout
Create a new branch based on the master branch
$ git branch
Create a new tracking branch with reference to the current branch
$ git checkout –track
Deleting the current branch
$ git branch -d
Adding a tag to the current commit
$ git tag
Updating and Publishing
List all currently configured remotes
$ git remote -v
Show information about a remote
$ git remote show
Add new remote repository, named
$ git remote add
Download all changes from remote without merging with master
$ git fetch
Downloading changes and merging directly into the master
$ git pull
Publishing local changes on a remote
$ git push
Deleting a branch on the remote
$ git branch -dr
Publishing your tags
$ git push –tags
Merge & Rebase
Merge into the current master
$ git merge
Rebase your current master into
$ git rebase
Aborting a rebase
$ git rebase –abort
Continuing a rebase after post-conflict resolution
$ git rebase –continue
Using your configured merged tool to solve conflicts
$ git mergetool
Undo
Discard all changes in the working directory
$ git reset –hard master
Discarding local changes in a specific file
$ git checkout master
Reverting a commit
$ git revert
Resetting the master pointer to any previous commit and discarding all the changes made since then
$ git reset –hard
Preserving all changes as unstaged
$ git reset
Preserving uncommitted local changes
$ git reset –keep
🛰️ Join the Journey
Feel free to embark on this interstellar voyage with me. Clone, fork, or stargaze this repository to stay updated with the latest command revelations and cosmic Git insights. Together, we'll uncover the depths of version control and boldly code like no one has coded before.

May your merges be conflict-free and your commits evergreen! 🌱

Stay curious, stay cosmic! 🌌🖖

Vatsal!⚡ | @vatsalpatel1123


<h1>Creating a repository</h1>
<ul>
    <li>Clone an existing repository.</li>
    <ul>
        <li><code>$ git clone</code></li>
     </ul>   
    <li>Create an empty repository.</li>
    <ul>
        <li><code>$ git init</code></li>
    </ul> 
</ul>

<h1>2. Adding Local Changes: Git Cheat Sheet</h1>
Changed files in the working directory
Syntax: $ git status
Changes to track files
Syntax: $ git diff
Adding all the current changes to the next commit
Syntax: $ git add.
Adding some changes to the next commit
Syntax: $ git add -p
Commit all local changes in tracked files
Syntax: $ git commit -a
Commit previously staged changes
Syntax: $ git commit
Change the last commit
Syntax: $ git commit -amend


<h1>3. Commit History: Git Cheat Sheet</h1>
View all commits, starting from the latest one
Syntax: $ git log
Show all the changes made in a file in a specific period
Syntax: $ git log-p
Changes made by a person in a with timing
Syntax: $ git blame






<h1>4. Branches and Tags: Git Cheat Sheet</h1>
List all existing branches
Syntax: $ git branch -av
Switch master branch
Syntax: $ git checkout
Create a new branch based on the master branch
Syntax: $ git branch
Create a new tracking branch with reference to the current branch
Syntax: $ git checkout –track
Deleting the current branch
Syntax: $ git branch -d
Adding a tag to the current commit
Syntax: $ git tag


<h1>5. Updating and Publishing: Git Cheat Sheet</h1>
List all currently configured remotes
Syntax: $ git remote -v
Show information about a remote
Syntax: $ git remote show
Add new remote repository, named
Syntax : $ git remote add
Download all changes from remote without merging with master
Syntax: $ git fetch
Downloading changes and merging directly into the master
Syntax: $ git pull
Publishing local changes on a remote
Syntax: $ git push
Deleting a branch on the remote
Syntax: $ git branch -dr
Publishing your tags
Syntax: $ git push –tags






<h1>6. Merge & Rebase: Git Cheat Sheet</h1>


Merge into the current master
Syntax : $ git merge
Rebase your current master into
Syntax: $ git rebase
Aborting a rebase
Syntax: $ git rebase –abort
Continuing a rebase after post-conflict resolution
Syntax: $ git rebase –continue
Using your configured merged tool to solve conflicts
Syntax: $ git mergetool
Manually resolving conflicts with the help of the editor, and marking the file as resolved
Syntax: $ git add
Syntax: $ git rm

<h1>7. Undo: Git Cheat Sheet</h1>
Discard all changes in the working directory
Syntax: $ git reset –hard master
Discarding local changes in a specific file
Syntax: $ git checkout master
Reverting a commit
Syntax: $ git revert
Resetting the master pointer to any previous commit and discarding all the changes made since then
Syntax: $ git reset –hard
Preserving all changes as unstaged
Syntax: $ git reset
Preserving uncommitted local changes
Syntax: $ git reset –keep


<h1>8. Help and documentation: Git Cheat Sheet</h1>
Getting help on the command line
Syntax: $ git help



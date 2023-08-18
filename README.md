# 🚀 Unleash the Power of Git Commands! 💻

Welcome to my GitHub profile, where I've embarked on an adventure to explore the captivating realm of Git commands. 🌌 Here, you'll find a curated collection of my discoveries, experiments, and insights into the art of Git Commands. Whether you're a newbie explorer or a seasoned command-line voyager, there's something here for you!

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

<h1>Adding Local Changes</h1>
<ul>
    <li>Changed files in the working directory</li>
<ul>
    <li><code>$ git status</code></li>
</ul>
<li>Changes to track files</li>
<ul>
    <li><code> $ git diff</code></li>
</ul>
<li>Adding all the current changes to the next commit</li>
    <ul>
<li><code>$ git add .</code></li>
    </ul>
<li>Adding some changes to the next commit</li>
        <ul>
<li><code>$ git add -p</code></li>
             </ul>
<li>Commit all local changes in tracked files</li>
            <ul>
<li><code>$ git commit -a</code></li>
                 </ul>
<li>Commit previously staged changes</li>
                <ul>
<li><code>$ git commit</code></li>
                     </ul>
<li>Change the last commit</li>
                    <ul>
<li><code>$ git commit -amend</code></li>
 </ul> 
</ul>


<h1>Commit History</h1>
<ul>
    <li>View all commits, starting from the latest one</li>
    <ul>
<li><code>$ git log</code></li>
    </ul>
<li>Show all the changes made in a file in a specific period</li>
    <ul>
<li><code>$ git log-p</code></li>
    </ul>
<li>Changes made by a person in a with timing</li>
    <ul>
<li><code>$ git blame</code></li>
    </ul>
</ul>





<h1>Branches and Tags</h1>
<ul>
    <li>List all existing branches</li>
    <ul>
<li><code>$ git branch -av</code></li>
    </ul>
<li>Switch master branch</li>
    <ul>
<li><code>$ git checkout</code></li>
    </ul>
<li>Create a new branch based on the master branch</li>
    <ul>
<li><code>$ git branch</code></li>
    </ul>
<li>Create a new tracking branch with reference to the current branch</li>
    <ul>
<li><code>$ git checkout –track</code></li>
    </ul>
<li>Deleting the current branch</li>
    <ul>
<li><code>$ git branch -d</code></li>
    </ul>
<li>Adding a tag to the current commit</li>
    <ul>
<li><code>$ git tag</code></li>
    </ul>
</ul>


<h1>Updating and Publishing</h1>
<ul>
    <li>List all currently configured remotes</li>
    <ul>
<li><code>$ git remote -v</code></li>
    </ul>
<li>Show information about a remote</li>
    <ul>
<li><code>$ git remote show</code></li>
    </ul>
<li>Add new remote repository, named</li>
    <ul>
<li><code>$ git remote add</code></li>
    </ul>
<li>Download all changes from remote without merging with master</li>
    <ul>
<li><code>$ git fetch</code></li>
    </ul>
<li>Downloading changes and merging directly into the master</li>
    <ul>
<li><code>$ git pull</code></li>
    </ul>
<li>Publishing local changes on a remote</li>
    <ul>
<li><code>$ git push</code></li>
    </ul>
<li>Deleting a branch on the remote</li>
    <ul>
<li><code>$ git branch -dr</code></li>
    </ul>
<li>Publishing your tags</li>
    <ul>
<li><code>$ git push –tags</code></li>
    </ul>
</ul>






<h1>Merge & Rebase</h1>

<ul>
<li>Merge into the current master</li>
    <ul>
<li><code>$ git merge</code></li>
    </ul>
<li>Rebase your current master into</li>
    <ul>
<li><code>$ git rebase</code></li>
    </ul>
<li>Aborting a rebase</li>
    <ul>
<li><code>$ git rebase –abort</code></li>
    </ul>
<li>Continuing a rebase after post-conflict resolution</li>
    <ul>
<li><code>$ git rebase –continue</code></li>
    </ul>
<li>Using your configured merged tool to solve conflicts</li>
    <ul>
<li><code>$ git mergetool</code></li>
    </ul>
</ul>


<h1>Undo</h1>
<ul>
    <li>
Discard all changes in the working directory</li>
    <ul>
<li><code>$ git reset –hard master</code></li>
    </ul>
<li>Discarding local changes in a specific file</li>
    <ul>
<li><code>$ git checkout master</code></li>
    </ul>
<li>Reverting a commit</li>
    <ul>
<li><code>$ git revert</code></li>
    </ul>
<li>Resetting the master pointer to any previous commit and discarding all the changes made since then</li>
    <ul>
<li><code>$ git reset –hard</code></li>
    </ul>
<li>Preserving all changes as unstaged</li>
    <ul>
<li><code>$ git reset</code></li>
    </ul>
<li>Preserving uncommitted local changes</li>
    <ul>
<li><code>$ git reset –keep</code></li>
    </ul>
</ul>


## 🛰️ Join the Journey

Feel free to embark on this interstellar voyage with me. Clone, fork, or stargaze this repository to stay updated with the latest command revelations and cosmic Git insights. Together, we'll uncover the depths of version control and boldly code like no one has coded before.

May your merges be conflict-free and your commits evergreen! 🌱

_Stay curious, stay cosmic!_ 🌌🖖

<b> _Vatsal!⚡ | @vatsalpatel1123_ </b>






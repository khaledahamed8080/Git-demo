# Git-demo 
THIS REPOSITORY IS FOR DEMO PURPOSE
<h1>SETUP</h1> 
Configuring user information used across all local repositories
<h2>git config --global user.name “[firstname lastname]”</h2>
set a name that is identifiable for credit when review version history
<h2>git config --global user.email “[valid-email]”</h2>
set an email address that will be associated with each history marker
<h2>git config --global color.ui auto</h2>
set automatic command line coloring for Git for easy reviewing

<h1>SETUP & INIT</h1>
Configuring user information, initializing and cloning repositories
<h2>git init</h2>
initialize an existing directory as a Git repository
<h2>git clone [url]</h2>
retrieve an entire repository from a hosted location via URL

<h1>STAGE & SNAPSHOT</h1>
Working with snapshots and the Git staging area
<h2>git status</h2>
show modified files in working directory, staged for your next commit
<h2>git add [file]</h2>
add a file as it looks now to your next commit (stage)
<h2>git reset [file]</h2>
unstage a file while retaining the changes in working directory
<h2>git diff</h2>
diff of what is changed but not staged
<h2>git diff --staged</h2>
diff of what is staged but not yet commited
<h2>git commit -m “[descriptive message]”</h2>
commit your staged content as a new commit snapshot

<h1>BRANCH & MERGE</h1>
Isolating work in branches, changing context, and integrating changes
<h2>git branch</h2>
list your branches. a * will appear next to the currently active branch
<h2>git branch [branch-name]</h2>
create a new branch at the current commit
<h2>git checkout</h2>
switch to another branch and check it out into your working directory
<h2>git merge [branch]</h2>
merge the specified branch’s history into the current one
<h2>git log</h2>
show all commits in the current branch’s history

<h1>INSPECT & COMPARE</h1>
Examining logs, diffs and object information
<h2>git log</h2>
show the commit history for the currently active branch
<h2>git log branchB..branchA</h2>
show the commits on branchA that are not on branchB
<h2>git log --follow [file]</h2>
show the commits that changed file, even across renames
<h2>git diff branchB...branchA</h2>
show the diff of what is in branchA that is not in branchB
<h2>git show [SHA]</h2>
show any object in Git in an-readable format

<h1>SHARE & UPDATE</h1>
Retrieving updates from another repository and updating local repos
<h2>git remote add [alias] [url]</h2>
add a git URL as an alias
<h2>git fetch [alias]</h2>
fetch down all the branches from that Git remote
<h2>git merge [alias]/[branch]</h2>
merge a remote branch into your current branch to bring it up to date
<h2>git push [alias] [branch]</h2>
Transmit local branch commits to the remote repository branch
<h2>git pull</h2>
fetch and merge any commits from the tracking remote branch

<h1>REWRITE HISTORY/h1>
Rewriting branches, updating commits and clearing history
<h2>git rebase [branch]</h2>
apply any commits of current branch ahead of specified one
<h2>git reset --hard [commit]</h2>
clear staging area, rewrite working tree from specified commit


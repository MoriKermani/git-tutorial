# A good summery of git commands
I just start learning git, so try to share it what I learned, and if you are
advance, help me to expand it, or you can just use it for learn and
review. enjoy :)

## The commands those should know to use git
- `git init` (initial git repository in .git).
- `git clone` (clone a repository into a new directory).
- `git add` (to staging the local changes).
- `git commit` (to store content permanetly in remote).
- `git status` (summary of the situation).
- `git push` (to send the changes to remote of repo. I suggest using this `git push origin branch-name`).
- `git log` (history of commits. my suggest is `git log --all --graph
    --decorate --oneline --date-order` to see history).
- `git branch` (create, show, and delete the branch. use `git push -d origin
    branch-name` to delete branch-name from remote repo).
- `git switch` (switch between branches).
- `git checkout` (switch branches or restore working tree files).
- `git merge` (to merge a branch to this branch that you are in it. also you can see
    the all commits of the another one branch. if use `git merge --squash`, you
    can merge the last commit of that branch to your branch, so you have just
    one commit instead of all commits of that branch, and this is so clearly and
    readable one line commits.)
- `git rebase` (to change the base of this branch to HEAD of another branch.
    use `git rebase -i` for intractive).
- `git fetch` (what is the changes of repository that you are working with another, before you pull it and merge it).
- `git pull` (to get a repository to your local things) `git pull = git fetch + git merge`.
- `git show` (show details about commit).
- `git tag` (put tag in your commit).
- `git reflog` (to see HEAD's numbers in log stage).
- `git reset` (reset your current branch and working directory to a HEAD before).
- `git revert` (to undo changes that you have pushed).
- `git grep` (to search string in any version of the project. if leave version in commit, it will search for all the files).
- `git cat-file commit hash` (see commit details with hash. also you can search specificly for tree of that with ```git ls-tree``` and see the contens of file data with `git cat-file blob`).
- `git diff` (show changes between commits, commit and working tree, etc).
- `git submodules add (repo's address)` (to use a repository for a part of your repository).
- `git commit --amend` (to chandge the last commit ).
- `git cherry-pick` (to apply specific commit from one branch onto another branch).
- `git stash` (to temporary save changes that you don't want to commit. for apply that use `git stash apply`).
- `git clean` (to remove untracked files and directories).
- `git am` (apply a series of patches from a mailbox).
- `git bisect` (use binary search to find the commit that introduced a bug).
- `git bundle` (move objects and refs by archive).
- `git citool` (graphical alternative to git-commit).
- `git describe` (give an object a human readable name based on an available
    ref).
- `git format patch` (prepare patches for e-mail submission).
- `git gc` (cleanup unnecessary files and optimize the local repository).
- `git remote -v` (show the remote that you are working on it).

### Upgrade
If there is a mistake or you can add more items, do me a favor and
upgrade the list.
Thank you.
add foo
add bar

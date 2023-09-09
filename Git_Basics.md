# Git and GitHub 

**Git** is a tool that tracks cahgnes on your local computer

**Github** is a website that stores your code remotely and makes it easy to work in a group.

## Git Commands To Remember

1. **clone** (pulls your code from github to local pc)
2. **status** (checks your git status)
3. **add** (adds changes to git for tracking)
4. **commit** (saves changes)
5. **push** (sends your code to a remote repo on github)

- **git** remote -v checks your url so you can see which branch you are working with remotely.

#### how to change from https: to git@

- **git** remote set-url origin git@github.com:*Name/repo name*

### How to initiate a commit on Git ###

1. **git** init
2. **git** status
3. **git** add . (or git add " name of the file needed to be added")
4. **git** commit -m (whatever commit message) **or**  git commit - "message 1" -m "extended instructions"
5. **git** status

### Things to note ###

<u> Green</u> indicates code that has been newly added.

<u>Red</u> indicates code that has been deleted since the last commit.

<u>White</u> indicates code that has not been touched/changed.

### How to push and pull 

**pull**

1. **git** clone (repository link found on github)

**push**

1. **git** push -u (repository link found on github) *do this for the initial push request*

>> otherwise

- **git** push *should be enough*



### workflows for git and github

1. **Github** write code >> commit changes >> make a pull request locally

2. **Git** write code >> git add >> git commit >> git push *if needed* git pull.


### Git branching

- **git** checkout -b (branchname) *creates a new branch*

- **git** checkout (branchname) *allows you to switch between branches*

- **git** diff (branch name) *can show you changes made on your code from a different branch*

- **git** branch -d (branch name) *deletes a branch after you are done working on it*

- **git** merge (branch name) *allows you to merge a branch to the main branch*
 

### Undoing on Git

- **git** reset (file name) *unstages recent adds*

- **git** reset HEAD~1 *uncommits recent changes*

>> #### To reset multiple changes

1. **git** log *to check all logs and see where to go back*

2. **git** reset (+ # of the commit you want to go back to)

- **git** reset --hard (+ # of a specific commit) *deletes all changes made since that specific commit*
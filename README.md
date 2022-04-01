In this session we are going to look at the basic concepts of git and github as developer



```What is Git```

Git is a Version control system that allows you to track files
and file changes in a repository (“repo”) 


```What is Github```

A web service for hosting your git repositories and
managing software projects (e.g. bug tracking, team
organisation)



Basic Terms in git 

Repository

A directory that has been "initialized" so that git can
record changes made to files within it.
Often shortened to "repo".
An initialized repository has a .git file in it.

Add (Stage) - (git add)

Adds a file to the “staging area” Tells git to add this file in
the next revision of the repository which allows you to
commit them. 

Commit (git commit -m “message”)

 Save changes to a repository. 

Diff - (git diff mybranch/myfile.html mysecondbranch/myfile.html )

Examine changes between two files

Master/Main Branch

A branch in Git is simply a lightweight movable pointer to
one of these commits.

Multiple Branches

You can work on multiple branches at the same time
git branch Shows all the branches of the code.
Create a branch with git branch <branch name>

Checkout

Switch to another branch
Checking out to another branch we use:
git checkout <branch name>

Merge

Join two or more branches
git merge merges the branch with the current branch

Merge Conflicts

When merged branches have different changes on the same line of
code, a conflict is created
When two different commits can’t be merged automatically. This is
need to be resolved manually.

Pull - (git pull)

Updating a local repository with changes from a remote
repo

Push - (git push)

Send commited changes from local repo to the remote
repository.

Clone - (git clone <URL>)

Makes a copy of the repo. Stores it to your local machine
(computer) 

“Fork” creates your own copy of someone else’s repo

Pull Request

Request to update a remote repo with changes from a
fork

History - (git log)

Shows a history of commits and messages.
Shows who made the change, when those changes were
made with a “message” 

Status- (git status)

Shows current changes to the repository. Show on
which branch you’re now.



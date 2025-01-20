# my_repo
My First Repository.\
Author - Dhruv Gupta \

Learning to use git 

- git clone <-some link-> -> clones the repository or whatever link from github to the current working directory.
- git status -> used to track the status of the files i.e whether they are the same as the github file or not.
- - Untracked - new files that git does not track yet.
- - modified - changes have occured.
- - staged - file is ready to be committed.
- - unmodified - unchanged.
- git add <-file name-> -> adds untracked or modified files in working directory to Git staging area
- git commit -m "some message" -> is the record of change
- git push origin main -> used to upload local commits to github for remote repo.
- git init -> used to make a normal directory a git repository.
- git remote add origin <-link-> -> used to establish a connection to a github repository.
- git remote -v -> TO check the connection once
- git branch -> To check the branch that we are working on.
- git branch -M <-branch name-> -> To rename the branch
- git push -u origin main -> push once and then we can use 'git push' for this purpose because of -u which stands for upstream.
- git checkout <-branch name-> -> navigate to the given branch
- git checkout -b <-new branch name-> -> birth/create a new branch
- git branch -d <-branch name-> -> to delete a branch and also can't perform this action when in the same branch.
- git diff <-branch name-> -> to compare commits, branches, files & more
- git merge <-branch name-> -> to merge two branches : can also do this via a Pull Request in GitHub itself.
- git pull origin <-branch name-> -> download content from a remote repo and immediately update the local repo to match that content.
- git reset <-file name-> -> reverse of git add operation.
- git reset -> to do multiple at once
- git reset HEAD~1 -> reduce by one commit to go to previous commit.
- git log -> we can check our commits. press 'q' to exit.
- git reset <-hash code-> -> from git log get the hash code to go to that particular commit.
- git reset --hard <-hash code-> -> vs code also removes the changes.

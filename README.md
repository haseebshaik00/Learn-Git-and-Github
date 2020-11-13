# Clone your own repo to local computer and push 
1) git clone "repo or .git url" : create a clone of your own repo
2) cd "repo" : move into your own repo
3) git add . : do changes and stage
4) git status : check the status
5) git commit -m "Message" : commit your changes
6) git branch -M main : rename master to main
7) git push -u origin main : push your changes to github

# Create a new repo on your local computer and push
1) First create a new repo on github and copy the repo or .git url
2) git init : initializa a git repo make sure the folder name is same as the repo name
3) git add . : do changes and stage
4) git status : check the status
5) git commit -m "Message" : commit your changes
6) git branch -M main : rename master to main
7) git remote add origin "repo or .git url" : add the remote url link
8) git push -u origin main : push your changes to github

# Branching
1) git branch : shows all the branches and the star indicates the current branch
2) git checkout -b "branch name" : creates a new branch and moves into it
3) git checkout "branch name" : switch in between branches
4) git diff : shows the changes (in red color) while you are in main branch
5) q : to get out of unchnaged type in cmd
6) git branch -d "branch name" : delete a branch
7) git merge main : merges main to the current branch to stay updated with the status of main (conflict may occur here)
8) git push --set-upstream origin "branch name" : to push a new branch

#Note
1) --set-upstream is same as -u
2) -u : when you write this you don't have to write origin "branch name" again and again
3) the merge conflicts can be prevented by the inbuilt vs code feature

# Pull request 
#When you do a commit in a branch(not main) then you can pull a request to main by clicking on the pull request option on github and hence merging it back to main

# Undoing in git

1) git reset : undoing a stage (undoing git add .), just write git reset if you want specify a file name, can check using git status command
2) git reset HEAD~1 : undoing a commit, HEAD pointer points to the previous commit and unstages the changes too
3) git log : displays the log of commits
4) git reset "commit-hash-code" : takes back to that commit
5) git reset --hard "commit-hash-code" : erases the latest updates

# Forking in git
#forking is done to use others code or to contribute to others code

# Some extra commands 

1) git add . :!"filename" : If you want to exclude some files from your git add .

# That's it!! Keep coding!!
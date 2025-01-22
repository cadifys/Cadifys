## 1 Create New Branch With Below Rule :
# Feature -> Feature/Feature_name
# Bug    --> Bug/Bug_title_orId
# Fix    -> Fix/Fix_title_OrId
# Improvement  -> Improv/Impro_title
# Issue     -> Issue/Issue_title_andId

## 2 Create Pull Request on UAT branch only :
# before you push rebase you code with UAT branch 
# PR discription should be good 
# and proper title

eg :
push changes
merge changes
rebase changes


xyz reviewer code => UAT
xyz code => Fear/branch => PR-UAT
push se rebase kr

push --force-with-lease

## 3 Commit with proper title :
# proper commet on your code 
# rebase your code with UAT 
eg commit - 
FIX : "Swiggy UI"
UPDATE
FEATURE

## 4 Some command for git :

git add . 
git commit -m "PROTO: added protocols"
git log --oneline


add a new branch - git checkout -b branch_name

edit the commit - git commit --amend
 

update a commit message 

update a file changes 

git commit --amend 
press i to insert update the commit message 
press esc then : then wq to save the changes 

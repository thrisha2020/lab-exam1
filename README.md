# lab-exam1
in first expermient we are cloning the repsoitory b using the 
$ git clone<httpa>
after creating the clone repository we are creating file by using add and commit method 
before that we need to add commomd touch to create file
$touch obe.c
$git add obe.c
$git commit -m "mesage"
we need to swtich to master before creating the newbranch
then now we need to caete newbranch by using command 
$git checkout -b newbranch
$touch two.c
$ git add two.c
$git commit -m "mesage"
now we need to merge newbarnch to master 
$ git checkout master
$git merge newbranch
now we to stash 
$ git stash save "message"
$git stash apply
we need to add message while creating the newbranch 
$ git commit -m "message for newbranch"
we are pushing the file from local to remote by using push command 
in the push method the files are uploaded to remote 
$git branch --v
$ git push
then again to we need to retrive the file we use command 
$ git pull
this allows the user to download the files back
for creating cherry-pick the command used is
cherry-pick is used to change the specific commit into the other commit 
$git checkout newbranch 
$ git add two.c
$git commit -m "mesage"
$git checkout master 
$git cherry-pick <commit id>
now we add tag for this commits we use command 
$ git tag v1.0
$git tag
we need to show those atges atached with commit id we use command 
$git show
to see the history of commits in this repository we use command
$ git log 
if we need to see this history in oneline we use command 
$git log --oneline
if we need to look up the reacent 4 commit sthe command is 
$git log -n 4
the last experiment is to revert the repository
swtich master 
look at the recent committs by using the git log 
$git revert <commit id>

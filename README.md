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

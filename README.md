<h1>Create a local repo</h1>
->create a folder(Project1)
->go to Project1
1. git init --> to initiate local repo
2. create a text file
3. git add text file
4. git commit -m "message for the commit"
5. create a repo in github portal and get the url
6. generate PAT
7. swith to required branch using
8. git branch -M master
9. check the branch
10. git branch
11. add remote repo url to local
12. git remote add origin https://github.com/prakashchconnect/Project1.git
13. push the local code to remote repo
14. git push -u origin master


<h1>Create a branch and push it to remote</h1>
1. git checkout -b branch1
2. check bit branch
3. git branch
4. swith to branch1
5. git checkout branch1
6. create a file
7. touch File1.txt
8. add some content to it
9. git add File1.txt
10. git commit
11. git push -u origin branch1
12. check the contents in git hub portal -->your branch should be there.(branch1)


<h1>merge the branch1 to master</h1>
NOTE: 1. i have added a file to branch1 in my local repo
2. i have added a file to master directly in ui(git hub)

1. git checkout master
2. git rebase origin/master
3. git commit
4. check out to branch1
5. git checkout branch1
6. merge the branch1 code to master
7. git push origin master
   
<h2>merge locally to main branch</h2>
2. checkout to master
3. git checkout master
4. merge feature branch to master
5. git merge feature1
6. push the local merge code to remote master branch
7. git push origin master
   
<h1>delete branch</h1>
<h3>delete locally</h3>
<ul>
<li>git branch -D branch3</li>
<li>delete remotely</li>
<li>git push origin :branch2</li>
<li>or</li>
<li>git push origin --delete branch2</li>
</ul>
<h3>to unstage or remove from git</h3>
<ul>
   <li>tests/.ipynb_checkpoints/helpers_tests-checkpoint.py</li>
</ul>
<h1 style="color:red;">GIT README.MD commands</h1>
<ul>
   <li>to use formatting use html elements</li>
</ul>

# learn-git
working with git command line

git init

git status // status of working tree

git add . // add all file

git add <file-name>
  
git commit -m <msg> // commit file change

git log // log all commit
  
git show <id> // show commit(id)'s content
  
git diff
  
staging area // when file was added
  
working dir //when file not yet added
  
git checkout -- <fileName> // discard the changes in working dir
  
git reset HEAD <fileName> // unstage, exchange from staging area to working dir

git checkout -b <branchName> // create new branch named 'branchName' and switch to it
  
git checkout <branchName> // switch to branch 'branchName'
  
git branch //list branchs now available
  
git branch -D <branchName> // delete branchName
  
git merge // merge branch A --> branch B

  git reset --soft <commitId>
  
  git reset --mixed <commitId>
  
  git reset --hard <commitId>

  git revert <commitId>
  
# Working with github
  
  git remove add origin <link>
  
  git push -u origin master/main
  
  git clone 
  
  git pull

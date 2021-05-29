# learn-git
working with git command line

git init

git status // status of working tree

git add . // add all file \n
git add <file-name>
  
git commit -m <msg> // commit file change

git log // log all commit \n
git show <id> // show commit(id)'s content \n
git diff
  
staging area // when file was added \n
working dir //when file not yet added \n
  
git checkout -- <fileName> // discard the changes in working dir\n
git reset HEAD <fileName> // unstage, exchange from staging area to working dir\n

git checkout -b <branchName> // create new branch named 'branchName' and switch to it\n
git checkout <branchName> // switch to branch 'branchName'\n
git branch //list branchs now available\n
git branch -D <branchName> // delete branchName\n
  
git merge // merge branch A --> branch B

# LearnGit
***How to use git***

## Lession 1:
* $ git init      `//using create .git`
* $ git status    `//using check status.`
* $ git add .     `//using add the new files in git.`
* $ git commit -m "[nameCommit]"  `//using write the commit for git.`

## Lession 2:
* $ git log       `//using open the commits history.`
* $ git show [commit id]      `//using display the content of commit history.`
* $ git diff      `//using display the change contents.`

## Lession 3:
* $ git checkout -- <file>    `//using remove the contents has modified.`
* $ git reset HEAD <file>     `//using the changes reset after using git add.`

## Lession 4:
* $ git branch                `//using display your branch is standing.`
* $ git checkout -b <branch> (branching)  `//using create a new branch.`
* $ git checkout <branch>                 `//choose branch you want use.`
* $ git branch -D <branch>                `//using delete a branch.`
* $ git merge <branch>                    `//using merge two branch A-->B.`

## Lession 5:
* $ git reset --soft <idCommit>           `//using call back to old committed but not git commit.`
* $ git reset -mixed <idCommit>           `//using call back to old committed but not git add.`
* $ git reset --hard <idCommit>           `//using call back to old committed but not git add and remove whole commit after it.`

## Lession 6:
* $ git revert <idCommit>                 `//using remove the contents of commit your call and save a new commit.`
* $ .gitignore                `//create .gitinore move files you aren't use in .gitinore you need not commit for that files.`

## Lession 7:
* $ git remote <name> <UrlGit>    `//Using remote to Github.`
* $ git remote -v                 `//using display the remote github.`
* $ git push                      `//using push up to Github.`
* $ git push origin <branch>      `//using push up the new branch to Github.`

## Lession 8:
* $ git clone <UrlClone>          `//using clone gitub.`
* $ git pull                      `//using merge Github and your computer.`
* $ git fetch origin <branch>     `//download orther branch in github.`

## Update content of Readme
* $ git --help
* $ git push --help
* $ git pull --help
* $ git reset --help
* $ git branch --help
* $ git checkout --help

This is my readme for github.....

Zaeds-MacBook-Air:desktop zaedsharba$ mkdir GitHubRepoAssignment
Zaeds-MacBook-Air:desktop zaedsharba$ cd GitHubRepoAssignment
Zaeds-MacBook-Air:GitHubRepoAssignment zaedsharba$ git init
Initialized empty Git repository in /Users/zaedsharba/Desktop/GitHubRepoAssignment/.git/
Zaeds-MacBook-Air:GitHubRepoAssignment zaedsharba$ touch readme.md
Zaeds-MacBook-Air:GitHubRepoAssignment zaedsharba$ git add .
Zaeds-MacBook-Air:GitHubRepoAssignment zaedsharba$ git log
fatal: your current branch 'master' does not have any commits yet
Zaeds-MacBook-Air:GitHubRepoAssignment zaedsharba$ open readme.md
Zaeds-MacBook-Air:GitHubRepoAssignment zaedsharba$ git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   readme.md

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   readme.md

Zaeds-MacBook-Air:GitHubRepoAssignment zaedsharba$ git add .
Zaeds-MacBook-Air:GitHubRepoAssignment zaedsharba$ git commit -m "modified readme.md"
[master (root-commit) 0d72b18] modified readme.md
 1 file changed, 1 insertion(+)
 create mode 100644 readme.md
Zaeds-MacBook-Air:GitHubRepoAssignment zaedsharba$ git status
On branch master
nothing to commit, working tree clean
Zaeds-MacBook-Air:GitHubRepoAssignment zaedsharba$ git remote add origin https://github.com/zaedsharba/GitHubRepoAssignment.git
Zaeds-MacBook-Air:GitHubRepoAssignment zaedsharba$ git push -u origin master
Counting objects: 3, done.
Writing objects: 100% (3/3), 242 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/zaedsharba/GitHubRepoAssignment.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.
Zaeds-MacBook-Air:GitHubRepoAssignment zaedsharba$ open readme.md
Zaeds-MacBook-Air:GitHubRepoAssignment zaedsharba$ 




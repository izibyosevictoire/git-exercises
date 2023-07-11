# git exercises
## bundle 1
### exercise 1



```bash
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint: 
hint:   git config --global init.defaultBranch <name>
hint: 
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint: 
hint:   git branch -m <name>
Initialized empty Git repository in /home/victoire/Videos/git exercises/.git/
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        one.html

nothing added to commit but untracked files present (use "git add" to track)
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git add .
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git commit -m "one.html"
[master (root-commit) ddeba5b] one.html
 1 file changed, 11 insertions(+)
 create mode 100644 one.html
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git branch -M main
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git remote add origin https://github.com/izibyosevictoire/git-exercises.git
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 369 bytes | 369.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/izibyosevictoire/git-exercises.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git checkout -b dev
Switched to a new branch 'dev'
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git push -u origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/izibyosevictoire/git-exercises/pull/new/dev
remote: 
To https://github.com/izibyosevictoire/git-exercises.git
 * [new branch]      dev -> dev
Branch 'dev' set up to track remote branch 'dev' from 'origin'.
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git checkout -b test
Switched to a new branch 'test'
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git push -u origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/izibyosevictoire/git-exercises/pull/new/test
remote: 
To https://github.com/izibyosevictoire/git-exercises.git
 * [new branch]      test -> test
Branch 'test' set up to track remote branch 'test' from 'origin'.
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git checkout dev
Switched to branch 'dev'
Your branch is up to date with 'origin/dev'.
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git branch -D test
Deleted branch test (was ddeba5b).
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git push origin --delete test
To https://github.com/izibyosevictoire/git-exercises.git
 - [deleted]         test

```
# exercise 2
``` bash

```
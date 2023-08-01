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
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ ^C
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git push -u origin dev
Branch 'dev' set up to track remote branch 'dev' from 'origin'.
Everything up-to-date
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git add .
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git commit -m "read me"
[dev b32b8d8] read me
 1 file changed, 78 insertions(+)
 create mode 100644 README.md
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git push -u origin dev
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.26 KiB | 1.26 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/izibyosevictoire/git-exercises.git
   ddeba5b..b32b8d8  dev -> dev
Branch 'dev' set up to track remote branch 'dev' from 'origin'.
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git stash -u
Saved working directory and index state WIP on dev: b32b8d8 read me
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git stash -u
Saved working directory and index state WIP on dev: b32b8d8 read me
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git stash -u
Saved working directory and index state WIP on dev: b32b8d8 read me
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git stash list
stash@{0}: WIP on dev: b32b8d8 read me
stash@{1}: WIP on dev: b32b8d8 read me
stash@{2}: WIP on dev: b32b8d8 read me
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git stash pop stash@{1}
Already up to date.
On branch dev
Your branch is up to date with 'origin/dev'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        about.html

nothing added to commit but untracked files present (use "git add" to track)
Dropped stash@{1} (7588e3734fb76b5f30adc93dbce4f77ec71d5ceb)
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git stash list
stash@{0}: WIP on dev: b32b8d8 read me
stash@{1}: WIP on dev: b32b8d8 read me
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git stash pop stash@{1}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        about.html
        home.html

no changes added to commit (use "git add" and/or "git commit -a")
Dropped stash@{1} (4a3de0600bc5d1622d50e603547cc5605a9302d8)
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git add .
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git commit -m "stash"
[dev 88a5c6d] stash
 3 files changed, 29 insertions(+), 3 deletions(-)
 create mode 100644 about.html
 create mode 100644 home.html
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git add .
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git commit -m "stash"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git checkout dev
Switched to branch 'dev'
Your branch is ahead of 'origin/dev' by 1 commit.
  (use "git push" to publish your local commits)
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git add .
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git commit -m "stash"
On branch dev
Your branch is ahead of 'origin/dev' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git push -u origin dev
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 612 bytes | 612.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/izibyosevictoire/git-exercises.git
   b32b8d8..88a5c6d  dev -> dev
Branch 'dev' set up to track remote branch 'dev' from 'origin'.
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git stash list
stash@{0}: WIP on dev: b32b8d8 read me
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git stash pop
Already up to date.
On branch dev
Your branch is up to date with 'origin/dev'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        team.html

nothing added to commit but untracked files present (use "git add" to track)
Dropped refs/stash@{0} (f9d1446741dd8fac673c1f006142b1ee25e50346)
victoire@victoire-Latitude-E7440:~/Videos/git exercises$ git reset --hard
HEAD is now at 88a5c6d stash
```
# bundle 2
## exercise 1
-git checkout -b ft/bundle-2
-git add .
-git commit -m "bundle-2 exercise 1

## exercise 2
my branches
  dev
  ft/bundle-2
* ft/service-redesign
  main
  ## exercise 3
ft/faq-page
  victoire@victoire-Latitude-E7440:~/Videos/the gym/git exercises$ git log
commit 82f04153a30cf12a586a34060677174b441d6c2f (HEAD -> ft/team-page, origin/ft/team-page)
Author: victoire <luandavicky5@gmail.com>
Date:   Tue Jul 25 10:15:33 2023 +0200

    exercise3

commit 36f400de2a99c34364b467b88926d937fa352a52 (origin/ft/service-redesign, ft/service-redesign)
Author: victoire <luandavicky5@gmail.com>
Date:   Thu Jul 13 17:19:54 2023 +0200

    added changes on service.html

commit 4c8464b34983e34c4930976b46e6311990dafa35 (origin/main, main, ft/contact-page)
Merge: 2efaf7a c05b2e3
Author: izibyosevictoire <114585574+izibyosevictoire@users.noreply.github.com>
Date:   Thu Jul 13 17:04:35 2023 +0200

    Merge pull request #2 from izibyosevictoire/ft/bundle-2
    
    test
:

Stashed changes

  
main
## Bundle 5
# Exercise 1
``` bash
victoire@victoire-Latitude-E7440:~/Videos/the gym/git exercises$ git add .
victoire@victoire-Latitude-E7440:~/Videos/the gym/git exercises$ git commit -m "bundle 5"
[main e44af0c] bundle 5
 1 file changed, 12 insertions(+)
 create mode 100644 index.html
victoire@victoire-Latitude-E7440:~/Videos/the gym/git exercises$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 437 bytes | 437.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/izibyosevictoire/git-exercises.git
   2312b76..e44af0c  main -> main
victoire@victoire-Latitude-E7440:~/Videos/the gym/git exercises

```
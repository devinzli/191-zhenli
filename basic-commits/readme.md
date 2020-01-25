**1. git status**

  devin@DESKTOP-5KQLU5C MINGW64 ~/repo/CS191/git-katas/basic-commits/exercise (master)
  $ git status
  On branch master

  No commits yet

  nothing to commit (create/copy files and use "git add" to track)

**2. git log**

  devin@DESKTOP-5KQLU5C MINGW64 ~/repo/CS191/git-katas/basic-commits/exercise (master)
  $ git log
  fatal: your current branch 'master' does not have any commits yet

**4. git status**

  devin@DESKTOP-5KQLU5C MINGW64 ~/repo/CS191/git-katas/basic-commits/exercise (master)
  $ git status
  On branch master

  No commits yet

  Untracked files:
    (use "git add <file>..." to include in what will be committed)

          new.txt

  nothing added to commit but untracked files present (use "git add" to track)

**6. git status**

  devin@DESKTOP-5KQLU5C MINGW64 ~/repo/CS191/git-katas/basic-commits/exercise (master)
  $ git status
  On branch master

  No commits yet

  Changes to be committed:
    (use "git rm --cached <file>..." to unstage)

          new file:   new.txt

**8. git status**

  devin@DESKTOP-5KQLU5C MINGW64 ~/repo/CS191/git-katas/basic-commits/exercise (master)
  $ git status
  On branch master
  nothing to commit, working tree clean

**10. git status**

  devin@DESKTOP-5KQLU5C MINGW64 ~/repo/CS191/git-katas/basic-commits/exercise (master)
  $ git status
  On branch master
  Changes not staged for commit:
    (use "git add <file>..." to update what will be committed)
    (use "git checkout -- <file>..." to discard changes in working directory)

          modified:   new.txt

  no changes added to commit (use "git add" and/or "git commit -a")

**12. git status**

  devin@DESKTOP-5KQLU5C MINGW64 ~/repo/CS191/git-katas/basic-commits/exercise (master)
  $ git status
  On branch master
  Changes to be committed:
    (use "git reset HEAD <file>..." to unstage)

          modified:   new.txt

**15. git status & git log**

  devin@DESKTOP-5KQLU5C MINGW64 ~/repo/CS191/git-katas/basic-commits/exercise (master)
  $ git status
  On branch master
  Changes not staged for commit:
    (use "git add <file>..." to update what will be committed)
    (use "git checkout -- <file>..." to discard changes in working directory)

          modified:   new.txt

  no changes added to commit (use "git add" and/or "git commit -a")

  devin@DESKTOP-5KQLU5C MINGW64 ~/repo/CS191/git-katas/basic-commits/exercise (master)
  $ git log
  commit 6f30897df7a3a207d0efabb86f92efcef7f725aa (HEAD -> master)
  Author: Zhen Li <devinzhenli@gmail.com>
  Date:   Fri Jan 24 18:02:06 2020 -0800

      changed again

  commit 893ef16ac2218f50007a3f53576b18cb2f99c513
  Author: Zhen Li <devinzhenli@gmail.com>
  Date:   Fri Jan 24 18:00:21 2020 -0800

      added a new file

Answer 1) 
        git version 2.36.1.windows.1

Answer 2)
     diff.astextplain.textconv=astextplain
      filter.lfs.clean=git-lfs clean -- %f
        filter.lfs.smudge=git-lfs smudge -- %f
        filter.lfs.process=git-lfs filter-process
        filter.lfs.required=true
        http.sslbackend=openssl
        http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
        core.autocrlf=true
        core.fscache=true
        core.symlinks=false
        pull.rebase=false
        credential.helper=manager-core
        credential.https://dev.azure.com.usehttppath=true
        init.defaultbranch=master
        core.editor="C:\Users\Aaron\AppData\Local\Programs\Microsoft VS Code\bin\code" --wait
        user.name=Aaron Reynolds
        user.email=ar796620@ohio.edu

Answer 3) 
        the command replies with a simple list of git commands, and describes how to use 
            many of their functions.

Answer 4)
        On branch master

        No commits yet

        Untracked files:
        (use "git add <file>..." to include in what will be committed)
              README.md
              answers.md

Answer 5)
    On branch master

    No commits yet

    Changes to be committed:
      (use "git rm --cached <file>..." to unstage)
           new file:   README.md

    Untracked files:
      (use "git add <file>..." to include in what will be committed)
            answers.md

Answer 6)
    On branch master

    No commits yet

    Changes to be committed:
      (use "git rm --cached <file>..." to unstage)
           new file:   README.md
           new file:   answers.md

Answer 7)
    On branch master
    Changes not staged for commit:
      (use "git add <file>..." to update what will be committed)
      (use "git restore <file>..." to discard changes in working directory)
            modified:   answers.md

    no changes added to commit (use "git add" and/or "git commit -a")

Answer 8)
    commit 929933c17d633dbe028285b84fb6693e1a27c4e3 (HEAD -> master)
    Author: Aaron Reynolds <ar796620@ohio.edu>
    Date:   Sat May 14 23:28:38 2022 -0400

     Initial commit

Answer 9)
    On branch main
    Your branch is up to date with 'origin/main'.

    Changes not staged for commit:
      (use "git add <file>..." to update what will be committed)
     (use "git restore <file>..." to discard changes in working directory)
           modified:   answers.md

    no changes added to commit (use "git add" and/or "git commit -a")

Answer 10)
     No

Answer 11)
        I am told that I cannot use the push command as there is data in a file that is not contained locally. And hints to me to use the command git pull first.

Answer 12
        Yes the changes that I made in my web browser were imported to my local files.

Answer 13


        Directory: C:\Users\Aaron\git-lab-2


        Mode                 LastWriteTime         Length Name
        ----                 -------------         ------ ----
        -a----         5/14/2022  11:52 PM            302 .gitignore
        -a----         5/14/2022  11:52 PM             11 README.md

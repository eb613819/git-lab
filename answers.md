Answer 1: git version 2.28.0.windows.1

Answer 2: diff.astextplain.textconv=astextplain
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
          credential.helper=manager
          core.editor="C:\Users\evanb\AppData\Local\Programs\Microsoft VS Code\Code.exe" --wait
          user.name=Evan Brooks
          user.email=eb613819@ohio.edu

 Answer 3:  usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
                [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
                [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
                [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
                <command> [<args>]

            These are common Git commands used in various situations:

            start a working area (see also: git help tutorial)
            clone             Clone a repository into a new directory
            init              Create an empty Git repository or reinitialize an existing one

            work on the current change (see also: git help everyday)
            add               Add file contents to the index
            mv                Move or rename a file, a directory, or a symlink
            restore           Restore working tree files
            rm                Remove files from the working tree and from the index
            sparse-checkout   Initialize and modify the sparse-checkout

            examine the history and state (see also: git help revisions)
            bisect            Use binary search to find the commit that introduced a bug
            diff              Show changes between commits, commit and working tree, etc
            grep              Print lines matching a pattern
            log               Show commit logs
            show              Show various types of objects
            status            Show the working tree status

            grow, mark and tweak your common history
            branch            List, create, or delete branches
            commit            Record changes to the repository
            merge             Join two or more development histories together
            rebase            Reapply commits on top of another base tip
            reset             Reset current HEAD to the specified state
            switch            Switch branches
            tag               Create, list, delete or verify a tag object signed with GPG

            collaborate (see also: git help workflows)
            fetch             Download objects and refs from another repository
            pull              Fetch from and integrate with another repository or a local branch
            push              Update remote refs along with associated objects

            'git help -a' and 'git help -g' list available subcommands and some
            concept guides. See 'git help <command>' or 'git help <concept>'
            to read about a specific subcommand or concept.
            See 'git help git' for an overview of the system.

Answer 4:   On branch master

            No commits yet

            Untracked files:
            (use "git add <file>..." to include in what will be committed)
                    README.md
                    answers.md

            nothing added to commit but untracked files present (use "git add" to track)

Answer 5:   On branch master

            No commits yet

            Changes to be committed:
            (use "git rm --cached <file>..." to unstage)
                    new file:   README.md

            Untracked files:
            (use "git add <file>..." to include in what will be committed)
                    answers.md

Answer 6:   On branch master

            No commits yet

            Changes to be committed:
            (use "git rm --cached <file>..." to unstage)
                    new file:   README.md
                    new file:   answers.md

Answer 7:   [master (root-commit) e8bacc5] Initial commit
            2 files changed, 78 insertions(+)
            create mode 100644 README.md
            create mode 100644 answers.md
            PS C:\Users\evanb\desktop\cs2400\git-lab> git status
            On branch master
            Changes not staged for commit:
            (use "git add <file>..." to update what will be committed)
            (use "git restore <file>..." to discard changes in working directory)
                    modified:   answers.md

            no changes added to commit (use "git add" and/or "git commit -a")

Answer 8:   commit e8bacc590ddd3c8b1bb5eb7a756e5ed530db422d (HEAD -> master)
            Author: Evan Brooks <eb613819@ohio.edu>
            Date:   Fri Sep 4 14:29:04 2020 -0400

                Initial commit

Answer 9:   On branch master
            Your branch is up to date with 'origin/master'.

            Changes not staged for commit:
            (use "git add <file>..." to update what will be committed)
            (use "git restore <file>..." to discard changes in working directory)
                    modified:   answers.md

            no changes added to commit (use "git add" and/or "git commit -a")

Answer 10:  The changes I made online were not reflected in my local copy.

Answer 11:  The git push command resulted in an error that said to pull before trying to push again.

Answer 12:  After using the command git pull, the changes I made online were finally reflected in my local copy.

Answer 13: Mode                LastWriteTime         Length Nam
           ----                -------------         ------ ----
           d--h--         9/4/2020   2:53 PM                .git
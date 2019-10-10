# temabit-lections-2019

## most used git commands

[`git help`](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/git-help.html)\
[`git init`](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/git-init.html)\
[`git config`](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/git-config.html)\
[`git clone`](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/git-clone.html)\
[`git checkout`](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/git-checkout.html)\
[`git branch`](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/git-branch.html)\
[`git status`](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/git-status.html)\
[`git add`](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/git-add.html)\
[`git commit`](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/git-commit.html)\
[`git push`](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/git-push.html)\
[`git fetch`](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/git-fetch.html)\
[`git pull`](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/git-pull.html)\
[`git merge`](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/git-merge.html)\
[`git tag`](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/git-tag.html)

## git help in bash `$ git --help`

### usage

git [--version] [--help] [-C \<path\>] [-c \<name\>=\<value\>] \
    [--exec-path[=\<path\>]] [--html-path] [--man-path] [--info-path] \
    [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare] \
    [--git-dir=\<path\>] [--work-tree=\<path\>] [--namespace=\<name\>] \
    \<command\> [\<args\>]

### These are common Git commands used in various situations

#### start a working area (see also: `git help tutorial`)
**<a name='clone'>`clone`**     [Clone a repository into a new directory](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/) \
**<a name='init'>`init`**      [Create an empty Git repository or reinitialize an existing one](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/)

#### work on the current change (see also: `git help everyday`)
**<a name='add'>`add`**       [Add file contents to the index](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/) \
   `mv`        Move or rename a file, a directory, or a symlink \
   `restore`   Restore working tree files \
   `rm`        Remove files from the working tree and from the index

#### examine the history and state (see also: `git help revisions`)
   `bisect`    Use binary search to find the commit that introduced a bug \
   `diff`      Show changes between commits, commit and working tree, etc \
   `grep`      Print lines matching a pattern \
   `log`       Show commit logs \
   `show`      Show various types of objects \
**<a name='status'>`status`**    [Show the working tree status](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/)

#### grow, mark and tweak your common history
**<a name='branch'>`branch`**    [List, create, or delete branches](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/) \
**<a name='commit'>`commit`**    [Record changes to the repository](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/) \
**<a name='merge'>`merge`**     [Join two or more development histories together](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/) \
   `rebase`    Reapply commits on top of another base tip \
   `reset`     Reset current HEAD to the specified state \
   `switch`    Switch branches \
**<a name='tag'>`tag`**       [Create, list, delete or verify a tag object signed with GPG](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/)

#### collaborate (see also: `git help workflows`)
**<a name='fetch'>`fetch`**     [Download objects and refs from another repository](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/) \
**<a name='pull'>`pull`**      [Fetch from and integrate with another repository or a local branch](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/) \
**<a name='push'>`push`**      [Update remote refs along with associated objects](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/)

**<a name='help'>`git help -a and git help -g`** [list available subcommands](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/) \
and some concept guides. See `git help <command>` or `git help <concept>` \
to read about a specific subcommand or concept. \
See `git help git` for an overview of the system.
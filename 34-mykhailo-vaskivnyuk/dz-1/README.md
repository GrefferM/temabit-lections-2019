# TEMABIT LECTIONS 2019

## most used git commands

[`git help`](#help)\
[`git init`](#init)\
[`git config`](#config)\
[`git clone`](#clone)\
[`git checkout`](#checkout)\
[`git branch`](#branch)\
[`git status`](#status)\
[`git add`](#add)\
[`git commit`](#commit)\
[`git push`](#push)\
[`git fetch`](#fetch)\
[`git pull`](#pull)\
[`git merge`](#merge)\
[`git tag`](#tag)

## $ git --help

### usage

git [--version] [--help] [-C \<path\>] [-c \<name\>=\<value\>] \
    [--exec-path[=\<path\>]] [--html-path] [--man-path] [--info-path] \
    [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare] \
    [--git-dir=\<path\>] [--work-tree=\<path\>] [--namespace=\<name\>] \
    \<command\> [\<args\>]

### These are common Git commands used in various situations

**start a working area (see also: git help tutorial)** \
**<a name='clone'>`clone`**     [Clone a repository into a new directory]() \
**<a name='init'>`init`**      [Create an empty Git repository or reinitialize an existing one]()

**work on the current change (see also: git help everyday)** \
**<a name='add'>`add`**       [Add file contents to the index]() \
   `mv`        Move or rename a file, a directory, or a symlink \
   `restore`   Restore working tree files \
   `rm`        Remove files from the working tree and from the index

**examine the history and state (see also: git help revisions)** \
   `bisect`    Use binary search to find the commit that introduced a bug \
   `diff`      Show changes between commits, commit and working tree, etc \
   `grep`      Print lines matching a pattern \
   `log`       Show commit logs \
   `show`      Show various types of objects \
**<a name='status'>`status`**    [Show the working tree status]()

**grow, mark and tweak your common history** \
**<a name='branch'>`branch`**    [List, create, or delete branches](https://mirrors.edge.kernel.org/pub/software/scm/git/docs/user-manual.html#manipulating-branches) \
**<a name='commit'>`commit`**    [Record changes to the repository]() \
**<a name='merge'>`merge`**     [Join two or more development histories together]() \
   `rebase`    Reapply commits on top of another base tip \
   `reset`     Reset current HEAD to the specified state \
   `switch`    Switch branches \
**<a name='tag'>`tag`**       [Create, list, delete or verify a tag object signed with GPG]()

**collaborate (see also: git help workflows)** \
**<a name='fetch'>`fetch`**     [Download objects and refs from another repository]() \
**<a name='pull'>`pull`**      [Fetch from and integrate with another repository or a local branch]() \
**<a name='push'>`push`**      [Update remote refs along with associated objects]()

**<a name='help'>`git help -a` and `git help -g` [list available subcommands and some]()
concept guides. See `git help <command>` or `git help <concept>` \
to read about a specific subcommand or concept. \
See `git help git` for an overview of the system.
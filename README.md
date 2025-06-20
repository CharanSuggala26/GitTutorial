# Git A-Z: The Complete Guide to Version Control 🚀

![Git Banner](https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png)

A complete  guide to Git version control system covering all essential commands and workflows from basic to advanced levels.

## 📚 Complete Git Tutorial Index (A-Z)

### A
- **`add`** - Stage files for commit
- **`amend`** - Modify the last commit
- **`alias`** - Create command shortcuts

### B
- **`branch`** - List/create/delete branches
- **`blame`** - Show who last modified each line
- **`bisect`** - Binary search through commits

### C
- **`commit`** - Record changes to repository
- **`clone`** - Copy a remote repository
- **`checkout`** - Switch branches or restore files
- **`cherry-pick`** - Apply specific commits
- **`clean`** - Remove untracked files

### D
- **`diff`** - Show changes between commits
- **`fetch`** - Download objects from remote
- **`rebase`** - Reapply commits on top of another branch

### E
- **`reset`** - Reset current HEAD to specified state
- **`revert`** - Revert existing commits
- **`remote`** - Manage remote repositories

### F
- **`fetch`** - Download objects from remote
- **`filter-branch`** - Rewrite branches
- **`fsck`** - Verify database integrity

### G
- **`grep`** - Search working directory
- **`gui`** - Graphical interface
- **`gc`** - Cleanup unnecessary files

### H
- **`help`** - Display help information
- **`hooks`** - Scripts triggered by Git events

### I
- **`init`** - Create empty Git repository
- **`ignore`** - Specify intentionally untracked files

### J
- **`(No major commands)`**

### K
- **`(No major commands)`**

### L
- **`log`** - Show commit logs
- **`ls-files`** - Show info about files
- **`ls-remote`** - List references in remote

### M
- **`merge`** - Join development histories
- **`mv`** - Move or rename file
- **`mergetool`** - Run merge conflict tool

### N
- **`notes`** - Add/inspect object notes

### O
- **`origin`** - Default remote name
- **`(Other remote names)`**

### P
- **`pull`** - Fetch and merge
- **`push`** - Update remote refs
- **`patch`** - Create patch files

### Q
- **`(No major commands)`**

### R
- **`rebase`** - Forward-port local commits
- **`reflog`** - Reference logs
- **`rm`** - Remove files
- **`remote`** - Manage remotes

### S
- **`status`** - Show working tree status
- **`stash`** - Save local modifications
- **`show`** - Display objects
- **`submodule`** - Manage subprojects

### T
- **`tag`** - Create/list/delete tags
- **`track`** - Set up tracking branches

### U
- **`update-index`** - Register file contents
- **`unstage`** - Remove from staging area

### V
- **`verify-tag`** - Verify tag signatures
- **`version`** - Display version info

### W
- **`whatchanged`** - Show logs with diffs
- **`worktree`** - Manage working trees

### X
- **`(No major commands)`**

### Y
- **`(No major commands)`**

### Z
- **`(No major commands)`**

## 🛠 Detailed Command Explanations

### Basic Workflow Commands

#### `git init`
Initialize a new Git repository:
```bash
git init
# Creates .git directory with all necessary files
# Git Add Command Reference

## Description
The `git add` command adds file contents to the staging area (index), preparing them for inclusion in the next commit.

## Basic Syntax
```bash
git add [options] [<pathspec>...]
```

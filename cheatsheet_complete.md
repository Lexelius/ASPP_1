# Cheat sheet for git
This cheat sheet (based on the official [Git Cheat Sheet](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf)) lists the most commonly used git commands.

<br>
## Setup
Configuring user information across all local repositories.

**Set a name that is identifiable for credit when review version history**

```git config --global user.name "[firstname lastname]"```

**Set an email address that will be associated with each history marker**

```git config --global user.email "[valid-email]"```

**Set default editor for writing commit messages**

```git config --global core.editor "[your favourite editor (e.g. emacs or vim)]"```

<br>
## Initialization
Starting a new repository or obtaining from an external source.

**Initialize an exisiting directory as a git repository**

```git init```

**Retrieve an entire repository from a hosted location via URL**

```git clone [url]```

## Stage & Snapshot
Working with snapshots and the git staging area.

**Show modified files in working directory, staged for your next commit**

```git status```

**Add a file as it looks now to your next commit (stage)**

```git add [file]```

**Unstage a file while retaining the changes in working directory**

```git reset [file]```

**Diff of what is changed but not staged**

```git diff```

**Diff of what is staged but not yet commited**

```git diff --staged```

**Commit your staged content as a new commit snapshot**

```git commit -m "[descriptive message]"```

<br>
## Branch & Merge
Isolating work in branches, changing context, and integrating changes.

**List your branches, a * will appear next to the currently active branch**

```git branch```

**Create a new branch at the current commit**

```git branch [branch-name]```

**Switch to another branch and check it out into your current working directory**

```git checkout [branch]```

**Merge the specific branch's history into your current one**

```git merge [branch]```

**Show all commits in the current branch's history**

```git log```

<br>
## Share & Update
Retrieving updates from another repository and updating local repos.

**Transmit local branch commits to a remote repository branch with given alias and branch name**

```git push [alias] [branch]```

**Transmit local branch commits to remote repository branch with default alias and same branch name**

```git push```

**Fetch and merge any commits from the tracking remote branch**

```git pull```






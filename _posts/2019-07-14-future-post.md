---
title: 'Visualizing git logs (and some gerrit tips)'
date: 2019-07-14
tags:
  - git
  - gerrit
---

I recently found that the command that I show you below is the most common one that I use. 
Sometimes when you work on a big git repo you need to understand where your current changes are in the git history and 
command like `git log` is of big help, but apparently there are multiple arguments to this line that could enhance overall visibility 
of this log. In particular I added the below aliases to `.gitconfig` to quickly see my status. 

```bash
[alias]
lg1 = log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all
lg2 = log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold cyan)%aD%C(reset) %C(bold green)(%ar)%C(reset)%C(bold yellow)%d%C(reset)%n''          %C(white)%s%C(reset) %C(dim white)- %an%C(reset)' --all
lg = !"git lg1"
lgs = !"git lg -10"
```

Then when I could use `git lg` or `git lgs` to get something like this: 

![alt text](https://nd7141.github.io/files/git-lg.png)



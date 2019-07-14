---
title: 'Nicely formatting git logs (and some gerrit tips)'
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

![alt text](/files/git-lg.png)

This helps me to quickly see, which branch I'm in comparing to the overall history, who committed what and when, 
and quickly navigate in the logs. 

#### A word on gerrit 
[Gerrit](https://www.gerritcodereview.com/) is a code review tool often used within software enterprises to manage large repositories.
If you want to have a shortcut to the repos that you work on, then go to *Settings*->*Preferences* and add a new url that will appear at the top of gerrit page.

![alt text](/files/gerrit.jpg)

Example of url is the following and depends on the name of your repo. 

```bash
#/dashboard/?title=Alpha+team&Scala+open=is:open+project:enterprise/rnn-prospecting-eligibility&Python+open=is:open+project:enterprise/rnn-prospecting-eligibility-python&Recently+closed=is:closed+project:enterprise/rnn-prospecting-eligibility+OR+project:enterprise/rnn-prospecting-eligibility-python+limit:15
```

This will display a url named *Alpha* at the top of the page that will lead to recent commits of the corresponding projet. No need to use search anymore. 






# [fit] Git: rebase
# [fit] From Chaos to Order

<br/>

```swift
let author = "Konstantin Portnov"
let github = "github.com/x0000ff"
```

<br/>

![inline 60%](./img/logo.png)

![right](./img/yoda.jpg)

^ https://i.pinimg.com/736x/d8/f7/bc/d8f7bc72c1ca0361bb647eaffc501aed--yoda-images-movieposter.jpg

---

# What is git rebase?

---

# Feature branch is outdated...

![inline](./img/feature-branch-outdated.png)

---

# a little bit

![inline](./img/feature-branch-very-outdated.png)

---

# Change the base?
# "re-base"?
# 🤔

^ https://wac-cdn.atlassian.com/dam/jcr:e4a40899-636b-4988-9774-eaa8a440575b/02.svg?cdnVersion=iq

---

# Atlassian is liar!

![inline](./img/incorrect-rebase.gif)

^ https://cdn-images-1.medium.com/max/1600/1*mgyl38slmqmcE4STS56nXA.gif

---

# Atlassian fixed!

![inline](./img/correct-rebase.gif)

^ https://wuistalking.files.wordpress.com/2016/09/what-is-a-rebase.gif

---

# Let's do it!

![inline](./img/make-simple-rebase.png)

---

# Magic is in progress

![inline](./img/vzhuh.jpeg)

^ https://beatmaker.tv/Default/General/Image/f8b5c54e-c2f0-47f6-ba84-fc28c9edc0be?type=TrackImageOriginal&ver=0

---

# Result

![inline](./img/after-simple-rebase.png)

---

# Result

![inline](./img/feature-branch-outdated-compare.png)

---

# Practice

Feel free to practice in repo:
`./practice-here/rebase-simple`

---

# Can I have a conflict?

![inline](./img/conflict.png)

---

# `master`

![inline](./img/master-before-conflict.png)

---

# `feature`

![inline](./img/feature-before-conflict.png)

---

# Let's try to rebase

![inline](./img/try-rebase.png)

---

# Oops

![inline](./img/rebase-failed.png)

---

# Oops

![inline](./img/rebase-failed-2.png)

---

# Oops

![inline](./img/rebase-failed-3.png)

---

# Fix 

![inline](./img/fix-conflict.gif)

---

# Fix 

![inline](./img/rebase-failed-4.png)

---

# Fixed

![inline](./img/rebase-fixed.png)

---

# I really love this cat

![inline](./img/vzhuh.jpeg)

^ https://beatmaker.tv/Default/General/Image/f8b5c54e-c2f0-47f6-ba84-fc28c9edc0be?type=TrackImageOriginal&ver=0

---

# Fixed

![inline](./img/rebase-fixed-2.png)

---


# Practice

Feel free to practice in repo:
`./practice-here/rebase-conflict`

---

# Just replay commits?

![inline](./img/boring.jpg)

---

# You can make it interactive 

```
$ git rebase --interactive HEAD~1

#################################

pick 0fcd976 Drop me

# Rebase b06684f..0fcd976 onto b06684f (1 command(s))
#
# Commands:
# p, pick = use commit
# r, reword = use commit, but edit the commit message
# e, edit = use commit, but stop for amending
# s, squash = use commit, but meld into previous commit
# f, fixup = like "squash", but discard this commit's log message
# x, exec = run command (the rest of the line) using shell
# d, drop = remove commit
```

---

# `pick`

> p, pick = use commit

![inline](./img/interactive-pick.gif)

---

# `reword`

> r, reword = use commit, but edit the commit message


![inline](./img/interactive-reword.gif)

---

# `edit`

> e, edit = use commit, but stop for amending

After make the changes you have to: 
- add changed file by "`git add`"
- continue rebase with command "`git rebase --continue`"

---

# `edit`

> e, edit = use commit, but stop for amending

![inline](./img/interactive-edit.gif)

---

# `squash`

> s, squash = use commit, but meld into previous commit

![inline](./img/interactive-squash.gif)

---

# `fixup`

> f, fixup = like "squash", but discard this commit's log message

![inline](./img/interactive-fixup.gif)

---

# `exec`

> x, exec = run command (the rest of the line) using shell

![inline](./img/interactive-exec.gif)

---

# `exec` can be massive 😎

```
$ git rebase --interactive --exec "md5 README.md" HEAD~3
```

![inline](./img/interactive-exec-massive.gif)

---

# `drop`

> d, drop = remove commit

![inline](./img/interactive-drop.gif)

---

# More info:

- https://git-scm.com/book/pt-br/v2/Git-Branching-Rebasing
- https://www.atlassian.com/git/tutorials/rewriting-history/git-rebase
- https://hackernoon.com/mastering-git-why-rebase-is-amazing-a954485b128a

---


# Q & A
# 🤔

---

# Thanks a lot!

☺️

![30% right fit](./img/thanks.jpg)

---

# **Me...**

![right 50%](./img/me.jpeg)

- ![:inline:](./img/me.jpeg) Konstantin Portnov 

- ![:inline:](./img/favicon.ico) [http://about.me/x0000ff](http://about.me/x0000ff)

- ![:inline:](./img/github.png) [https://github.com/x0000ff](https://github.com/x0000ff)

- ![:inline:](./img/twitter.png) [https://twitter.com/x0000ff](https://twitter.com/x0000ff)

- ![:inline:](./img/linkedin.png) [https://www.linkedin.com/in/KonstantinPortnov](https://www.linkedin.com/in/KonstantinPortnov)

---

# This Presentation
# 🙂
# http://bit.ly/2yuMmKC

---

# EOF
# 🍻
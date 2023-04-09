---
layout: post
title: Git and Github Stuffs
date: 2023-04-05 15:09:00
description: It is just some random stuff
tags: git version-control
categories: tech
---

这一篇我简单粘贴一些 Git 和 Github 的 基础操作。
由于信息都可以通过网上检索到。因此部分写成 SOP 的形式。

# Installation

I use mac so I use homebrew.

```zsh
$ brew install git
```

# Git

虽然很难想象不使用 Github 的 Git，但是还是放一些到这里。我现在没时间写这些。

- version check:
  - `git --version`

# GitHub CLI (Command-line interface)

和 GitHub 交互, 我们可以选择打开网页 github desktop 或者 github CLI。使用 CLI 不解释。

## CLI 安装

- install
  - `brew install gh`
- upgrade
  - `brew upgrade gh`

# Github

# SOP: Set up git username and email for a new repo/mac

1. install homebrew
2. install git, gh
3. setup global username and email with:
   ```
    $ git config --global user.name "YOUR_NAME"
    $ git config --global user.email "YOUR_EMAIL"
   ```
4. Authentication with gh: `$ gh auth login` and follow instruction.
5. **更换用户** repeat 3 - 4.

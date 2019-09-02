---
title: 【git】强制覆盖本地代码（与git远程仓库保持一致）
date: 2019-09-02 11:44:33
categories: "git"
tags: "git"
---

### git强制覆盖：
```
    git fetch --all
    git reset --hard origin/master
    git pull
```
### git强制覆盖本地命令（单条执行）：
```
    git fetch --all && git reset --hard origin/master && git pull
```
# git 学习

## git帮助

解决`fatal: '/usr/local/git/share/doc/git-doc': not a documentation directory.`的问题：[参见](https://blog.csdn.net/qq_22073849/article/details/88947065)

```bash
git help --web log
```

## git配置

```bash
git config --local -l
git config --global --list
git config --system --list

git config --gloabl user.name 'gloomyblack'
git config --global user.email 'gloomyblack@gmail'
git config user.name
```

## git状态和日志

```bash
git status
git log | cat
```

## 工作区和暂存区

```bash
# 将当前已经跟踪的所有文件添加到暂存区
git add -u
# 给文件重命名的简单方法
git mv name newname
```

## 版本历史

```bash
# 当前分支历史
git log
# 所有分支历史
git log --all
# 图形化历史
git log --all --graph
# 简洁列表
git log --online -n2
# 基于提交创建分支
git checkout -b temp e79fdec5792d
```

## git图形化工具

```bash
gitk
```

## .git

```bash
git init
```
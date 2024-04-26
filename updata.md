要更新你 fork 的仓库以反映原始仓库的更改，你可以执行以下步骤：

确保你当前在本地的项目目录中。
添加原始仓库作为远程仓库：

```bash
git remote add upstream https://github.com/tangly1024/NotionNext.git
```

拉取原始仓库的更改：

```bash
git fetch upstream
```

将你的主分支切换到你 fork 的主分支（通常是 main 或 master）：

```bash
git checkout main
```

合并原始仓库的更改到你的主分支：

```bash
git merge upstream/main
```

这些步骤将使你的主分支与原始仓库保持同步。如果使用的是不同的分支名称，请将命令中的 main 替换为你实际使用的分支名称。

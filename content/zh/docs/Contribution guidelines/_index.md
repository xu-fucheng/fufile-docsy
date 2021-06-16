---
title: "贡献指南"
linkTitle: "贡献指南"
weight: 10
description: >
  罗马并非一天建成的。
---

### 签署贡献者许可协议
在我们合并您的pull request前，我们需要您签署贡献者许可协议。

### 代码约定
+ JavaDoc不使用@author，因为随着更新的人增多，JavaDoc将变得臃肿。Git提交记录中将公平地记录您的贡献。
+ 项目中所有新建的文件顶部要添加ASF许可注释，可以从现有文件中复制。

### 贡献流程
+ Fork Fufile项目
+ clone到本地
+ 从希望贡献的分支中创建新的分支，trunk分支不允许pull request，可以从dev分支创建。
+ 提交您的更改，并签署dco。
+ 将新分支推送到您fork的仓库。
+ 在提交pull request前，请将您的仓库与远程代码同步，避免产生冲突并使提交记录清晰。
```git
git remote add upstream git@gitee.com:xufucheng/fufile.git
git fetch upstream
git rebase upstream/dev
git checkout -b your_awesome_patch
... add some work
git push origin your_awesome_patch
```
+ 申请pull request，并等待回复。
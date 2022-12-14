# Review Policy

## 什么时候需要 Review ?

- 功能性的更改，新文档，新描述

如果一项功能非常简单，无功能性的修改且申请 Review 有点浪费其他人的时间，则可以不进行 Review 。通常包含以下场景：

- 错别字更改
- 行末空白符号删除

## 接受一个 PR

一个 PR 只需要一个 Approval 就可以提交到主线。任何人都可以表达自己接受一个 PR ，但通常情况下我们需要接受 PR 的人有良好的判断能力。

## 如何实际应用 PR

通常情况下，一个 PR 在被接受后，需要 rebase 到最新的主分支，然后将多余的 commit 压缩为一个。在主线上形成一个 "squash commit" 。我们通常用命令行完成这项任务。

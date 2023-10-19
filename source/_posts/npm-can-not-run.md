---
title: npm项目无法运行
date: 2023-10-19 11:23:07
tags: 技术
---

- nvm切换node版本
- 网络原因无法下载依赖（切换淘宝源或科学上网）
- 删除node_modules和package-lock.json，重新npm i
- npm cache clean -n
- 重新vscode，重启终端或有些文件无写权限可通过此解决

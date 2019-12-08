---
title: "如何用 hugo 搭建个人博客"
date: 2019-12-05T21:34:12+08:00
draft: false
---

# 第一步 下载安装并配置Hugo
1. 下载:在 [Hugo Releases](https://github.com/gohugoio/hugo/releases)中下载压缩包，选择你的系统类型对应的那一个
2. 安装:将压缩包解压到 D:\Software\hugo 里
3. 配置:把 D:\Software\hugo 加到 PATH 中
4. 重启终端，在命令行运行 `hugo version` 查看版本

# 第二步 快速搭建博客
1. 进入[hugo官网](https://gohugo.io/) ，点击 Quick Start 快速开始
2. 从 step2 开始抄写代码并运行，直到step7（注意：部分step可能有多个命令，一定要全部执行）
3. 得到一个public目录，这就是我们的博客站点
4. 运行`hugo server -D` 可以预览草稿，运行`hugo server`可以预览非草稿
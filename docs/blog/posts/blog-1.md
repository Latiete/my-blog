---
date:
  created: 2025-07-31
  updated: 2025-07-31
readtime: 15
author: 杨志恒
tags:
  - 博客
  - 示例
draft: false
---

# Agent 生成 UML 图

本文介绍本人利用 Agent 生成 UML 图的实践经验。

<!-- more -->

## 1.实践背景
7 月 21 组内周会上，leader 建议绘制一个项目的时序图，展示各个系统之间的交互，方便快速了解项目的流程。于是自己尝试利用 Agent 来协助制作了一个时序图，这篇文章用来分享一下利用 Agent 绘制各种 UML 图的实践经验。

## 2.前置环境
(1)Intellij IDEA  
(2)plantuml4idea 插件  
(3)Agent 插件，如：Cursor  
(4)模型选择: claude-sonnet-4  

![plantuml4idea](../../assets/plantuml4idea.png)

!!! info "注意"
	其中 plantuml4idea 插件需要 Graphviz 的支持，Windows 系统下载插件后就自带 Graphviz，但 Mac 系统需要自行安装，如果已经安装了安装包管理器 Homebrew，可以直接在终端输入:
    ```shell
    brew install graphviz
    ```
    安装完成后，可以通过以下命令验证：
    ```shell
    dot -V
    ```
    输出如图所示：
    ![dot-V](../../assets/dot-V.png)

## 3.效果展示

## 4.工作流程

### 1) 绘图 Prompt

### 2) 交互调整

### 3) 实践经验

#### a.UML 图的种类与颗粒度

#### b.图片保存问题


+++
author = "Newcon"
title = "LangChain Introduction"
date = "2023-06-01"
description = "LangChain Introduction"
tags = [
    "LangChain",
]
+++

## 目的
LangChain仓库：
[主仓库地址-Python版本](https://github.com/hwchase17/langchain)

还支持JS/TS仓库地址[LangChain.js](https://github.com/hwchase17/langchainjs)

LangChain对自己的定义是 `Building applications with LLMs through composability`

将这句话拆分解释一下：
1. LangChain目的是 Building applications，构建应用程序
2. 主要使用的工具是 LLMs (Large Language Model)，大语言模型
3. 使用的方法是 composability，composability是指将不同组件或模块组合在一起，以创建更大的系统或应用程序

通过上面的分解，可以看出LangChain的基本作用是什么了，你可以自行判断是否有必要使用 LangChain这个工具。

## 了解LangChain渠道

### 官方出品

- [官方帮助手册](https://python.langchain.com/en/latest/)，包含很多使用方法以及事例（不过都是英文写的...）
- 官方twitter [@LangChainAI](https://twitter.com/LangChainAI) -- 最多的内容是对LangChain的宣传，包含比较多的基于LangChain进行开发的其他案例，可以关注学习
- 创始人twitter [@hwchase17](https://twitter.com/hwchase17) -- 非常出色的创业家

2023年3月LangChain获得1000万美元种子轮融资，而LangChain仓库首次提交时间是 `2022-10-23`，用了5个月的时间获得融资

![2022-10-23](/images/commitLog.png)

### 其他

- 最近吴恩达和OpenAI团队成员出了学习视频["LangChain for LLM Application Development"](https://learn.deeplearning.ai/langchain/lesson/1/introduction) (TODO：分析课程内容)
- 一位1982年就进入AI领域的大佬 Mark Watson ，写了一本书 [LangChain and LlamaIndex Projects Lab](https://leanpub.com/langchain/read)，可以免费在线阅读，同时介绍了LangChain和LlamaIndex两个工具。非常羡慕大佬在这么大的年纪，还对工作与生活充满热情 :smile:  (TODO：分析此书的内容)
- 一位大佬写了一份教程，通过Jupyter 演示了几个例子 https://github.com/gkamradt/langchain-tutorials ，还有自己录制的教学视频，英文版的  (TODO：挑几个例子，做专门解析)
- 
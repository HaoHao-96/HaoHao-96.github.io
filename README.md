### 欢迎来到HaoHao's 主页！

### 环境

如果你安装了 [jekyll](http://jekyllcn.com/)，那你只需要在命令行输入 `jekyll serve` 或 `jekyll s`就能在本地浏览器中输入 `http://127.0.0.1:4000/`预览主题，对主题的修改也能实时展示（需要强刷浏览器）。

### 开始

你可以通用修改 `_config.yml`文件来轻松的开始搭建自己的博客:

```
# Site settings
title: BY Blog                    # 你的博客网站标题
SEOTitle: 柏荧的博客 | BY Blog		# SEO 标题
description: "Hey"	   	   # 随便说点，描述一下

# SNS settings  
github_username: qiubaiying     # 你的github账号
jianshu_username: e71990ada2fd  # 你的简书ID。

# Build settings
# paginate: 10              # 一页你准备放几篇文章
```

Jekyll官方网站还有很多的参数可以调，比如设置文章的链接形式...网址在这里：[Jekyll - Official Site](http://jekyllrb.com/) 中文版的在这里：[Jekyll中文](http://jekyllcn.com/).

### 撰写博文

要发表的文章一般以 **Markdown** 的格式放在这里 `_posts/`，你只要看看这篇模板里的文章你就立刻明白该如何设置。

yaml 头文件长这样:

```
---
layout:     post
title:      定时器 你真的会使用吗？
subtitle:   iOS定时器详解
date:       2016-12-13
author:     BY
header-img: img/post-bg-ios9-web.jpg
catalog: 	 true
tags:
    - iOS
    - 定时器
---

```

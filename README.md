# 修改主页

修改_config_yml文件，具体改法参见文件中注释

# 添加文档

以下是一篇文章 (2018-08-08-example.md) 的 YAML 头信息配置示例：

```
---
title: "示例文章标题"
date: 2018-08-08 08:08:08 +0800
category: Demo example
tags: [Minimalism, Demo]
comment: false
reward: false
excerpt: 这是这篇文章的摘要，或者你也可以在文章正文中使用 <!--more--> 标签来截断摘要。
---

正文内容
```

其中 category 和 tags 项一样，当有多个分类或标签时，有以下三种语法都是可行的：

```
---
category: Demo example
tags: Minimalism Demo

category: [Demo, example]
tags: [Minimalism, Demo]

category:
 - Demo
 - example
tags:
 - Minimalism
 - Demo
---
```

# 详细使用方法

本site框架为Minimalism，是基于github pages推荐的jekyll框架改进的web框架，使用简便。

详细使用方法见连接: <https://github.com/showzeng/Minimalism/wiki>
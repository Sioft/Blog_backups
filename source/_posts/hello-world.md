---
title: Hello World
---
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

# 第一博客

## 个人介绍

你好，这是我第一次写blog
<!--more-->
[siyunx的博客](https://sioft.github.io)
``` java
 hexo new "My New Post"
```
*列表1
- **列表2**
- 列表3
* 列表1
* 列表2
* 列表3

Apple
:   Pomaceous fruit of plants of the genus Malus in
    the family Rosaceae.

Orange
:   The fruit of an evergreen tree of the genus Citrus.

```python
        #!python
        # -*- coding: utf-8 -*-
        from flask import Flask, render_template

        app = Flask(__name__)
        app.debug = APP_DEBUG

        #homepage just for fun
        @app.route('/')
        def home():
            return render_template('index.html')
```

把鼠标停留在**HTML**和**W3C**上看会发生什么。

*[HTML]: Hyper Text Markup Language
*[W3C]: World Wide Web Consortium


Footnotes[^1] have a label[^@#$%] and the footnote's content.

[^1]: This is a footnote content.
[^@#$%]: A footnote on the label: "@#$%".

First Header  | Second Header
--------------|--------------
Content Cell  | Content Cell
Content Cell  | Content Cell

这是一个[链接](https://github.com/kamidox/blogs)
这是另外一种[链接][1]的形式

[1]: https://pythonhosted.org/Markdown/extensions/index.html

> 引用的文字内容
> 这是另外的引用内容

![图片描述](https://raw.githubusercontent.com/kamidox/blogs/master/kamidox_icon.png)

[TOC]

####hint类型的警告
!!! hint "subject of hint"
    Any number of other indented markdown elements.

####note类型的警告
!!! note "subject of note"
    Any number of other indented markdown elements.


## Quick Start

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/deployment.html)

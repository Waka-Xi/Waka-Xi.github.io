---
layout: post
title: Post.Template
published: false
---

1. 创建 post 只需要在_posts目录下新建个文件即可，这个文件需要遵循一定的格式，这是 jekyll 要求的，格式为 `YEAR-MONTH-DAY-title.MD`；
2. 所有的博客文件必须以YAML front-matter开头；
3. 文章想要提供摘要可以通过`<!-- more -->`(此值由`_config.yml`设置)或者变量`excerpt`；
4. 在 post 中添加图片资源：`![img]](/path/file.jpg)`;

front-matter 格式如下：

```yaml
---
layout: #布局文件，layouts
title: #标题，这个不受文件名影响
date: #日期
author: #作者
permalink: #静态链接
published: #是否发布文章，true/false
categories: #类别
tags: 
#标签，可以用[tag1, tag2]或者
#tags: 
#    - tag1
#    - tag2
comments: #评论，true/false
pinned: #置顶，true/false
excerpt: #摘要
toc: #开启目录，true/false
---
```

LOFFER 这个主题里面，写文可以直接复制一下默认内容，按需修改：

```yaml
---
toc: true
layout: post
comments: false
author: Robot_No.412
title: #标题
date: #日期
permalink: #静态链接
tags: #按需添加
excerpt: #摘要
---
```

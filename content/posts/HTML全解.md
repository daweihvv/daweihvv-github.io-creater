---
title: "HTML入门笔记1"
date: 2019-08-14
draft: false
---

## HTML的历史
* HTML是1990年由英国的李爵士发明的
  
## HTML的起手式
* 在vscode里HTML的起手式应该写为`!`,再按一下Tab就写出来了
```
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```
## 常用的表示章节的标签

* 表示文章/书的层级

* 标题　　　　　 　`h1~h6`
* 章节　　　　　　`section`
* 文章　　　　　　`article`
* 段落　　　　　　`p`
* 头部　　　　　　`header`
* 脚部　　　　　　`footer`
* 主要内容　　　　`main`
* 旁支内容　　　　`aside`
* 划分　　　　　　`div`    

## 全局属性
* 所有标签都有的属性
* `class `给你的标签分一个类
* `contenteditable`是任何一个元素可以被编辑
* `hidden`隐身属性
* `id`与class类似，号称自己有唯一的属性，但html并不能保证其唯一性,不到万不得已不要用
* `style`给一个指定风格
* `tabindex`用来控制Tab的顺序
* `title`用来显示完整的内容
  
## 常用的内容标签
* `ol+li`有序列表
* `ul+li`无序列表
* `dl+dt+dd`描述列表
* `pre`显示多个空格，回车，Tab等，一般与`code`配合写代码用
* `code`写代码用，常与`code`配合使用
* `hr`水平分割线
* `br`中断，打断（常用在换行）
* `a`超链接
* `em`强调语气
* `strong`强调内容
* `quote`引用（行内引用，内连引用）
* `blockquote`块级引用
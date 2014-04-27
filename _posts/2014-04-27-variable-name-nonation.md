---
layout: post
title:  "JavaScript 变量名标记法"
date:   2014-04-27
categories: javascript
---

刚开始学 JavaScript，想借用这小块地方做学习记录代码存放。

看了一二十页的《JavaScript 高级程序设计》，虽然只是了解一点点乏味的知识，但我相信坚持下去会有收获的。

首先是变量名的标记法，在《JavaScript 高级程序设计》里面说了三种分别是 Camel 标记法，Pascal 标记法和匈牙利类型标记法。

Camel 标记法——首字母是小写的，接下来的单词都以大写字母开头。例如：

{% highlight javascript %}
var myTestValue = 0 , mySecondTestValue = "hi" ；
{% endhighlight %}

Pascal 标记法——首字母是大写的，接下来的单词都以大写开头，例如：

{% highlight javascript %}
var MyTestValue = 0 , MySecondTestValue = "hi" ；
{% endhighlight %}

匈牙利类型标记法——在以 Pascal 标记法命名的变量前附加一个小写字母（或小写字母序列），说明该变量的类型。例如，i 表示整数，s 表示字符串，如下所示：

{% highlight javascript %}
var iMyTestValue = 0 , sMySecondTestValue = "hi" ；
{% endhighlight %}
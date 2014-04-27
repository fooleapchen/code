---
layout: post
title:  "JavaScript 变量名标记法"
date:   2014-04-27
categories: javascript
---

刚开始学 JavaScript，想借用这小块地方做学习笔记。

看了一二十页的《JavaScript 高级程序设计》，虽然只是了解一点点乏味的知识，但我相信坚持下去会有收获的。

首先是变量名的标记法，在《JavaScript 高级程序设计》里面说了三种分别是 Camel 标记法，Pascal 标记法和匈牙利类型标记法。

Camel 标记法——首字母是小写的，接下来的单词都以大写字母开头。例如：

{% highlight javascript %}
var myTestValue = 0 , mySecondTestValue = "hi" ；
{% endhighlight %}

Pascal 标记法——首字母是大写的，接下来的单词都以大写开头。例如：

{% highlight javascript %}
var MyTestValue = 0 , MySecondTestValue = "hi" ；
{% endhighlight %}

匈牙利类型标记法——在以 Pascal 标记法命名的变量前附加一个小写字母（或小写字母序列），说明该变量的类型。例如，i 表示整数，s 表示字符串，如下所示：

{% highlight javascript %}
var iMyTestValue = 0 , sMySecondTestValue = "hi" ；
{% endhighlight %}

手头上的《JavaScript 高级程序设计》是第一版的，提了这三个标记法之后，作者用匈牙利标记法命名并全书遵循。

我下载第二版及第三版的PDF，第二版只是带过顺便提一下 Camel 标记法，而第三版干脆不提。理应来说应该越来越详细才对，不知道为何这部分省略，鄙人在以匈牙利标记法码字的时候感觉很常忘记大写，我想也可能是这个原因吧——麻烦。

**本文历史**

* 2014-04-27 完成初稿
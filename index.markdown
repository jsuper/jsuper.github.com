---
layout: name
title: Home

section: Home
---

<img class='inset right' src='/images/tangling.png' title='Tang Ling' alt='Photo of Mark Reid drinking a coffee' width='120px' />

Welcome
=======
我是[Tony](/info)，是一名计算机程序开发工程师，喜欢研究新的技术, 如Golang和Node.js等, 也比较喜欢折腾一些古老的编辑器(如Emacs); 也喜欢阅读。如果想了解更多关于我的信息，请点击本页上的各种链接。


+--	{.section}
Research
========
主要从事Java平台相关工作。目前就职于叠拓信息技术有限公司（成都），负责开发和维护爱立信MINI-LINK Craft软件。
=--

+-- {.section}
Blogs
=====
目前正在维护的博客叫 _[Explorer of Programming](/blog)_ 主要记录我在计算机编程领域的一些心得和体会。最新的文章包括:
{% for post in site.categories.blog limit:3 %}
<ul class="compact recent">
<li>
	<a href="{{ post.url }}" title="{{ post.excerpt }}">{{ post.title }}</a>
	<span class="date">{{ post.date | date_to_string }}</span> 
</li>
</ul>
{% endfor %}
=--

+-- {.section}
[Reading](http://librarything.com/home/jsuper)
==============================================
<script type="text/javascript" src="http://www.librarything.com/jswidget.php?reporton=jsuper&amp;show=recent&amp;header=&amp;num=8&amp;covers=small&amp;text=title&amp;tag=show&amp;css=0&amp;style=2&amp;version=1"> </script>
=--

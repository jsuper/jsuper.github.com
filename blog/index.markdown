---
layout: blog
title: Home
section: Home

feed: atom.xml
keywords: Java, Blog
---

我的编程技术心得和体会
==========================================

[Tony](/)的技术博客, 记录了我的一些编程相关的心得和体会. 

关于本博客的更多[信息](info.html) , 以及其相关的 [链接和资源](kith.html), 以及[所有的博客文章](past.html)都可以通过页面最上方的链接获取.

[![Feed icon](/files/css/feed-icon-14x14.png){:title="Atom feed of recent posts" .right}][订阅]
同样也可以[订阅][] 本博客最新的文章.

[订阅]: /blog/atom.xml

最近更新
------------

{% for post in site.categories.blog limit:5 %}
<div class="section list">
  <h1>{{ post.date | date_to_string }}</h1>
  <p class="line">
  <a class="title" href="{{ post.url }}">{{ post.title }}</a>
  <a class="comments" href="{{ post.url }}#disqus_thread">View Comments</a>
  </p>
  <p class="excerpt">{{ post.excerpt }}</p>
</div>
{% endfor %}

<p>
<a href="past.html">过去的文章 &rarr;</a>
</p>

<script type="text/javascript">
    //<![CDATA[
    /* * * CONFIGURATION VARIABLES: EDIT BEFORE PASTING INTO YOUR WEBPAGE * * */
    var disqus_shortname = 'explorerofprogramming'; // required: replace example with your forum shortname

    /* * * DON'T EDIT BELOW THIS LINE * * */
    (function () {
        var s = document.createElement('script'); s.async = true;
        s.type = 'text/javascript';
        s.src = '//' + disqus_shortname + '.disqus.com/count.js';
        (document.getElementsByTagName('HEAD')[0] || document.getElementsByTagName('BODY')[0]).appendChild(s);
    }());
//]]>
</script>
---
layout: page
title: 金须百炼，矢不轻发。
tagline: Supporting tagline
---
{% include JB/setup %}

时间一点点的流逝，回忆着已经度过的二十多年里，有许多美妙的事情，而展望未来，真是不知还有哪些困难和幸福，一个在路上的人，该深刻的思考，为了那逝去的美丽和未来的无限可能。


我是[王海良](http://cn.linkedin.com/in/wanghailiang)，一个八零后创业者，寻求着不一样的人生经历。

> Look, if you had one shot, or one opportunity to seize everything you ever wanted. One moment, Would you capture it or just let it slip?


## 文章列表

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

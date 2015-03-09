---
layout: page
title: Welcome to lgfang's Blog
tagline: 你看你，每一天都想放弃，但每一天又都坚持下来了
---
{% include JB/setup %}

Please be noted that, in addition to blogs underneath, you also have access to
[all my notes](./notes/index.html)

<br/>

{% for post in site.posts limit: 5 %}

<a style="color:#4A4A4A;font-size:160%" href="{{ post.url }}"> {{ post.title }}</a>

{{ post.excerpt }}

<br/>

{% endfor %}

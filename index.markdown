---
layout: post
title: Xiangqi's Corner
---
大家好，我是Xiangqi.


<p><br /><b>博客:</b></p>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>

<p><br /><b>邮箱:</b></p>

<blockquote>
<p>
wuhui911@foxmail.com
</p>
</blockquote>



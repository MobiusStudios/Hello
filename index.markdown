---
layout: default
title: Xiangqi's Corner
---

Hi there, I am Peter Wang, an [Open Source][oss] enthusiast. This site is
dedicated to providing information about [me](resume.html) and [what I do](/work).


<p><br /><b>My Blog:</b></p>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>

<p><b>Find me on:</b></p>

<ul>

<li><a href="https://github.com/xiangqiz/">Github</a></li>

</ul>
<p><br /><b>Contact Information:</b></p>

<blockquote>
欢迎所有朋友加我微信：xiangqiz
</blockquote>

[oss]:http://en.wikipedia.org/wiki/Open_source

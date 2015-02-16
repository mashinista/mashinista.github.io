---
layout: page
title: Mashinista's Jekyll
tagline: work in progress &#9997;
---
{% include JB/setup %}

<img src="https://camo.githubusercontent.com/2752c82268f4afc52bdf3b74d2de323d00a7f818/68747470733a2f2f662e636c6f75642e6769746875622e636f6d2f6173736574732f3239363433322f3439313439302f36373861653731632d626132662d313165322d393530352d3465393163363366373239632e706e67">

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




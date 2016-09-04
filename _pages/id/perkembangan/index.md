---
layout: page
order: 2
parent: index
permalink: /id/perkembangan/
title: Perkembangan
---

<ul>{% for post in site.posts %}
  <li>{{ post.date | date: "%Y-%m-%d" }}
    <h2><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h2>
  </li>{% endfor %}
</ul>

<p>Langganan <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

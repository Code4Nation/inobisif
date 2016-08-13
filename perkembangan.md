---
layout: page
title: Perkembangan
permalink: /id/perkembangan/
order: 2
---

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

      <h2>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </h2>
    </li>
  {% endfor %}
</ul>

<p class="rss-subscribe">Langganan <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

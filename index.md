---
layout: default
---

<blockquote>
  <h1>Ekonomi Desa&nbsp;ke&nbsp;Kota</h1>
  <p>Bagaimana kita dapat melibatkan petani, nelayan, dan masyarakat perdesaan
    ke dalam mata rantai bisnis sehingga meningkatkan taraf hidup mereka?</p>
  <p>Dapatkah teknologi informasi meningkatkan keterlibatan masyarakat perdesaan
    ke dalam ekonomi nasional?</p>
  <p><a href="/id/konsep">PELAJARI KONSEP</a></p>
</blockquote>

{% for post in site.posts limit:1 %}
<h2>Perkembangan Terkini: {{ post.title }}</h2>
<section>
    {{ post.content }}
</section>
{% endfor %}

{% include konsep-banner.html %}

---
layout: default
title: AEOSprout
---

<h1>AEOSprout 🌱</h1>
<p style="font-size: 1.2rem;">Grow content into AI answers.</p>

<hr>

<h2>🌱 About</h2>
<p>I’m learning how content gets discovered, understood, and surfaced by AI.</p>

<h2>🧠 Latest Posts</h2>

{% for post in site.posts %}
  <div style="margin-bottom: 2rem;">
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p style="color: gray;">{{ post.date | date: "%b %-d, %Y" }}</p>
  </div>
{% endfor %}

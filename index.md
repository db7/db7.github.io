---
layout: default
title: Home
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small><em>{{ post.date | date: "%B %d, %Y" }}</em></small><br>
    </li>
  {% endfor %}
</ul>

---


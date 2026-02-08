---
layout: default
---

# Welcome to AnalitykaXG

Here you can find all my football data analyses.

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%B %d, %Y" }}
  </li>
{% endfor %}
</ul>

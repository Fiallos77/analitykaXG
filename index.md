---
layout: default
title: AnalitykaXG
---

# Welcome to AnalitykaXG

Here you can find all my football data analyses — tactical insights, heatmaps, xG metrics, and passing networks.

---

<ul>
{% for post in site.posts %}
  <li style="margin-bottom: 20px;">
    {% if post.image %}
      <img src="{{ post.image | relative_url }}" alt="{{ post.title }}" style="width:150px; float:left; margin-right:10px; border-radius:5px;">
    {% endif %}
    <a href="{{ post.url | relative_url }}" style="font-size: 18px; font-weight: bold;">{{ post.title }}</a><br>
    <small>{{ post.date | date: "%B %d, %Y" }}</small>
    <div style="clear: both;"></div>
  </li>
{% endfor %}
</ul>

---

### About this site
AnalitykaXG is my personal football data analysis portfolio. Here I explore tactical patterns, player statistics, and team performance using heatmaps, xG metrics, and passing networks. All posts are generated from my own analysis and Python/Power BI visualizations.

---
title: "GA4GH::Metadata News"
layout: default
permalink: /news.html
category:
  - news
---

## {{ page.title }}

{% for item in site.categories.news %}
  {% assign currentdate = item.date | date: "%Y" %}
  {% if currentdate != date %}
<h3 id="y{{item.date | date: "%Y"}}">{{ currentdate }}</h3>
   {% assign date = currentdate %}
  {% endif %}
<div class="excerpt">
{{ item.excerpt }}
<p>{{ item.date | date: "%Y-%m-%d" }}: <a href="{{ item.url | relative_url }}">more ...</a></p>
</div>
{% endfor %}

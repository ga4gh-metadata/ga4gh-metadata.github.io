---
title:  "GA4GH::Metadata Examples & Guides"
layout: default
permalink: /howto.html
category:
  - howto
---

## {{ page.title }}

{% for item in site.categories.howto %}
<div class="excerpt">
{{ item.excerpt }}
<p><a href="{{ item.url | relative_url }}">more ...</a></p>
</div>
{% endfor %}

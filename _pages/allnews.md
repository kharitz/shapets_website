---
title: "News"
layout: default
excerpt: "ShapETS"
sitemap: false
permalink: /allnews.html
---

# News
{% for article in site.data.news %}
<p>{{ article.date }} 
<em>{{ article.headline | markdownify}}</em></p>
{% endfor %}

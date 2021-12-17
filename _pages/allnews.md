---
title: "News"
layout: textlay
excerpt: "ShapETS"
sitemap: false
permalink: /allnews.html
---

# News
{% for article in site.data.news %}
<ul><li>{{ article.date }}{{ article.headline | markdownify}}</ul></li>
{% endfor %}

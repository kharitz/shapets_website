---
title: "News"
layout: textlay
excerpt: "ShapETS"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
**[{{ article.date }}]** 
<em>{{ article.headline | markdownify}}</em>
{% endfor %}

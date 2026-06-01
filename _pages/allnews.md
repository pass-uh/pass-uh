---
title: "News"
layout: textlay
excerpt: "Allan Lab at Leiden University."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p style="color: #478dd8;">{{ article.date }}</p> 
  {{ article.headline | markdownify}}
<br>
{% endfor %}

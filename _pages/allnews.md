---
title: "News"
layout: textlay
excerpt: "The Computational Molecular Design Lab at the University of Barcelona"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}

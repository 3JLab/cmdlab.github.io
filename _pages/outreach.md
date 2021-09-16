---
title: "Computational Molecular Design Lab - Outreach"
layout: gridlay
excerpt: "Computational Molecular Design Lab -- Outreach"
permalink: /outreach/
---

# Outreach and Other Interests

Communicating the science we do and getting everyone curious about it is an important aspect of the work as researcher. The page below highlights some work the group does in this area and has done in the past.

Also keep an eye on twitter, and the news section for exciting outreach updates!

## Highlights
{% assign number_printed = 0 %}
{% for publi in site.data.outreach %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
<a href="{{ publi.link.url }}"><img src="{{ site.url }}{{ site.baseurl }}/images/outreach/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" /></a>
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.team }}</em></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

#### Follow us on Social media:
[**Twitter**](https://twitter.com/jjuarez_jimenez)

### Publications
<ol>
{% for publi in site.data.outreachpub %}

  <li>{{ publi.title }}</li>
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
</ol>





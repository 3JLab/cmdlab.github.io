---
title: "Computational Molecular Design Lab - team"
layout: gridlay
excerpt: "Computational Molecular Design Lab: Team members"
sitemap: false
permalink: /team/
---

# Group Members



## Team Lead

<div>
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/portrait.JPG" class="img-responsive" width="15%" style="float: left" />
  <h4>Jordi Juárez-Jiménez</h4>
  <i>Lecturer, March 2020 -<br>
  <i>Marie Sklodowska-Curie Fellow, Sep 2015 - Sep 2017<br>email: [jordi.juarez@ub.edu](mailto:jordi.juarez@ub.edu)<br>
    A full CV is available [here]({{ site.url }}{{ site.baseurl }}/downloads/cv-placeholder.pdf). </i>
  <i>itemscope itemtype="https://schema.org/Person"><a itemprop="sameAs" content="https://orcid.org/0000-0003-1464-1397" href="https://orcid.org/0000-0003-1464-1397" target="orcid.widget" rel="me noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon">https://orcid.org/0000-0003-1464-1397</a></i>
  <ul style="overflow: hidden">
  <li> Graduated in Pharmacy, University of Barcelona </li>
  <li> PhD University of Barcelona with  <a href="https://PERFIL DE JAVI.html">F. Javier Luque</a> </li>
  <li> Postdoc University of Florida with <a href="PERFIL ADRIAN">Adrian Roitberg</a> </li>
  <li> Postdoc University of Edinburgh with <a href="http://www.julienmichel.net/lab/">Julien Michel</a> </li>
 </ul>

 </div>

  

## Team Members
  
  
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  {{ member.info }}
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}



## Master and Bachelor Students
{% assign number_printed = 0 %}
{% for member in site.data.students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

# Joining the group

### Open Positions

**Expression of interest:** Please send an email to [Jordi Juarez](mailto:jordi.juarez@ub.edu). 

### Applications for PhD and Postdoc positions

INFO WILL BE UDPDATED TO THIS WEBSITE SOON. If you are interested in joining the group in the meantime get in touch [here](mailto:jordi.juarez@ub.edu) 

If there is no specific opening advertise take a look at some of the following opportunities for PhD students:   
 

And for Postdocs:   
* [Marie Curie Fellowship](https://ec.europa.eu/research/mariecurieactions/actions/individual-fellowships_en)   


Generally if you are looking for postdoc funding, there is a great resource for fellowships/fundinding opportunities around the world:
[postdoc funding schemes](https://asntech.github.io/postdoc-funding-schemes/)

   
### Undergraduate student projects

INFO WILL BE UDPDATED TO THIS WEBSITE SOON. If you are interested in joining the group in the meantime get in touch [here](mailto:jordi.juarez@ub.edu)

### Summer student projects
 

## Former visitors, BSc/ MSc students
<div class="row">

<div class="col-sm-4 clearfix">
<h4>Bachelor Students</h4>
{% for member in site.data.alumni_bsc %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Master students</h4>
{% for member in site.data.alumni_msc %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Visitors</h4>
{% for member in site.data.alumni_visitors %}
{{ member.name }}
{% endfor %}
</div>

</div>

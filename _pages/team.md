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
  <i>Marie Sklodowska-Curie Alumni<br>email: [jordi.juarez@ub.edu](mailto:jordi.juarez@ub.edu)<br>
    A full CV is available [here]({{ site.url }}{{ site.baseurl }}/downloads/cv-placeholder.pdf). </i><br>
  <a itemprop="sameAs" content="https://orcid.org/0000-0003-1464-1397" href="https://orcid.org/0000-0003-1464-1397" target="orcid.widget" rel="me noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon">https://orcid.org/0000-0003-1464-1397</a>
  <ul style="overflow: hidden">
  <li> Graduated in Pharmacy, University of Barcelona </li>
  <li> PhD University of Barcelona with  <a href="http://www.ub.edu/cbcg/team/fjluque/"> Prof. F. Javier Luque</a> </li>
  <li> Visiting PhD student University of Bologna with  <a href="https://www.unibo.it/sitoweb/andrea.cavalli"> Prof. Andrea Cavalli</a> </li>
  <li> Postdoc University of Florida with <a href="https://roitberg.chem.ufl.edu/"> Prof. Adrian Roitberg</a> </li>
  <li> Postdoc University of Edinburgh with <a href="http://www.julienmichel.net/lab/">Dr. Julien Michel</a> </li>
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
## **WE ARE RECRUITING!**

We want to incorporate a full-time researcher at the Predoctoral level to work on in silico development of PPI glues. Further details are provided [here]({{ site.url }}{{ site.baseurl }}/downloads/PREDOC_RESEARCHER.pdf) 

**Expression of interest:** Please send an email to [Jordi Juarez](mailto:jordi.juarez@ub.edu). 

### Applications for PhD and Postdoc positions

If there is no specific opening advertise take a look at some of the following opportunities for PhD students:   

* [FPU fellowships](https://www.educacionyfp.gob.es/servicios-al-ciudadano/catalogo/general/99/998758/ficha/998758-2020.html) from the Ministerio de Ciencia, Innovación y Universidades (In Spanish).
* [FI fellowships](https://agaur.gencat.cat/en/beques-i-ajuts/convocatories-per-temes/Ajuts-per-a-la-contractacio-de-personal-investigador-novell-FI-2021) from the Generalitat de Catalunya.
* [PredocsUB fellowships](http://www.ub.edu/beques/3rcicle/PREDOCSUB/index.html) from the University of Barcelona (In Catalan).
* [FI-SDUR program](http://www.ub.edu/beques/3rcicle/FI-SDUR/index.html) Joint program between the Generalitat de Catalunya and the University of Barcelona

And for Postdocs:   
* [Marie Curie Fellowship](https://ec.europa.eu/research/mariecurieactions/actions/individual-fellowships_en) 
* [Juan de la Cierva formación e Incorporación](http://www.aei.gob.es/portal/site/MICINN/menuitem.dbc68b34d11ccbd5d52ffeb801432ea0/?vgnextoid=5cd919af71af5710VgnVCM1000001d04140aRCRD)(Link in Spanish)
* [Margarita Salas y Maria Zambrano Fellowships](https://www.universidades.gob.es/portal/site/universidades/menuitem.43f867cc076c14d185cacc2c026041a0/?vgnextoid=0ede5b38feee8710VgnVCM1000001d04140aRCRD&vgnextchannel=cc3cd58bc3350710VgnVCM1000002006140aRCRD) (Link in Spanish)

If you get confused navigating the Spanish system of postdoctoral fellowships (Who could blame you?!) just get in [touch](mailto:jordi.juarez@ub.edu)

Generally if you are looking for postdoc funding, there is a great resource for fellowships/fundinding opportunities around the world:
[postdoc funding schemes](https://asntech.github.io/postdoc-funding-schemes/)
 
### Undergraduate student projects

**We offer 2 Treballs de fi de grau (TFGs) a l'ensenyament  farmacia**

- Exploring the applicability of Alphafold models to drug design
- Isothermal Titration Calorimetry: Physicochemical principles and applications to drug discovery (Bibliographic)

Information about inscription and admission can be found [here](https://www.ub.edu/portal/web/farmacia/graus/-/ensenyament/detallEnsenyament/483731/15)

If you are a Pharmacy Student at the University of Barcelona and you are interested in developing your own TFG subject just get in [touch](mailto:jordi.juarez@ub.edu)

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

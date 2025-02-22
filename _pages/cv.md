---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* PhD in Biotechnology, Universitat de Barcelona (Spain), 2019 
* Biohealth Computing Erasmus Mundus Master,Université Joseph Fourier (France), 2014
* Bachelor’s degree in Biochemistry, Universitat de Barcelona (Spain), 2013

Work experience
======
* Part-time fellow, Spanish Cancer Association (“Asociación Española Contra el Cáncer”), 2011-2012

* Ph.D. fellow (scholarship from ‘La Caixa’ Foundation), Universitat de Barcelona (Spain), 2014-2018 

* Research Associate in the project ‘PT17/0009/00018 ISCIII- Platform of Bioinformatics of Carlos III Health Institute, metabolomics node’. Universitat de Barcelona (Spain), 2019-2020

* Research Associate in the project “Countering the metabolic reprogramming associated with metastasis and resistance to treatment to prevent therapeutic failure in prostate and colon cancer”. Universitat de Barcelona (Spain), 2020-2021

* Research Associate working in modelling, analysing and interpretation of genomic and multi-omic data. BHF Cardiovascular Epidemiology Unit. Department of Public Health and Primary Care. University of Cambridge (United Kingdom), 2021-

Publications
======
{% if site.author.googlescholar %}
  <div class="wordwrap">You can find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% comment %}
this is commented out
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
{% endcomment %}  

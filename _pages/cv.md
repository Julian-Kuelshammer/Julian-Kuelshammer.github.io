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
* Diploma in Mathematics (Second Subject: Computer Science) at the University of Bonn, Germany, December 2009
* Ph.D in Mathematics at the University of Kiel, Germany, May 2012

Work experience
======
* October 2007 -- September 2009: Student assistant
  * University of Bonn, Germany

* December 2009 -- September 2012: Scientific Assistant
  * University of Kiel, Germany

* October 2012 -- March 2016: Scientific Assistant
  * University of Stuttgart, Germany

* April 2016 -- March 2018: DFG Postdoc
  * University of Stuttgart, Germany

* April 2018 -- August 2018: Scientific Assistant
  * University of Stuttgart, Germany

* September 2018 -- today: Senior lecturer/Associate professor 
  * Uppsala University, Sweden
  * Parental leave 100&#37;: January--August 2021
  * Docent title (roughly equivalent to German habilitation): 31.05.2022. [Docent lecture slides on Catalan combinatorics](/files/catalan_combinatorics.pdf)
  * Parental leave 50&#37;: September 2022--June 2023
  * [Distinguished University teacher](https://www.uu.se/en/staff/faculty/science-and-technology/recruitment-promotion-and-merit/promotion-docent-and-distinguished-teacher/distinguished-university-teachers): 12.12.2025.

Academic distinctions
=====
* International Conference on Representations of Algebras (ICRA) 2018 Award

Research grants
======
* January 2025 -- December 2028: VR project grant "Quivers, exact categories, and A-infinity algebras"
  * Total: 4080000 SEK 

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

  
Teaching
======

As Lecturer
-----

  <ul>{% for post in site.teaching %} {% if post.role == "Lecturer" %}
    {% include archive-single-cv.html %}
  {% endif %}
  {% endfor %}</ul>
  
As Teaching Assistant
-----

<ul>{% for post in site.teaching %} {% if post.role == "Teaching assistant" %}
    {% include archive-single-cv.html %}
  {% endif %}
  {% endfor %}</ul>


  
Service
======
* Programme Coordinator for the [Master Programme in Mathematics](https://www.uu.se/en/admissions/master/selma/program/?pKod=TMA2M) at Uppsala University (2020--2023)
* Director of [Postgraduate Studies in Mathematics](https://www.uu.se/en/department/mathematics/study/phd-studies) at Uppsala University (2024--2026)
* Maintainer of [FDLIST](https://fdlist.math.uni-bielefeld.de/)
* Organiser of [FD Seminar](https://www.fd-seminar.xyz/) (2020--2024)
* Editor for [Communications in Algebra](https://www.tandfonline.com/journals/lagb20/about-this-journal#editorial-board) (April 2025--)

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
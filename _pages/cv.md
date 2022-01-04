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

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
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

<ul>{% for post in site.teaching %} {% if post.role == "Teaching&nbsp;Assistant" %}
    {% include archive-single-cv.html %}
  {% endif %}
  {% endfor %}</ul>

Academic distinctions
=====
* International Conference on Representations of Algebras (ICRA) 2018 Award
  
Service
======
* Maintainer of [FDLIST](https://fdlist.math.uni-bielefeld.de/)
* Organiser of [FD Seminar](https://www.fd-seminar.xyz/)

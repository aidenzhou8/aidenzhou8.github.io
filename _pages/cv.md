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
* B.S. in Computer Science and Mathematics, Yale University, Expected [Year]
  * Relevant Coursework: Algorithms, Data Structures, Machine Learning, Linear Algebra, Probability Theory

Work experience
======
* [Position Title], [Company/Organization], [Time Period]
  * [Description of responsibilities and achievements]

* [Position Title], [Company/Organization], [Time Period]
  * [Description of responsibilities and achievements]
  
Skills
======
* Programming Languages: Python, Java, C++, JavaScript, [others]
* Technologies: Machine Learning, Data Science, Web Development
* Tools: Git, Linux, [others]

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
* [Add your service and leadership activities here]

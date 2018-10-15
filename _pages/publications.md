---
layout: archive
title: "Selected publications"
permalink: /publications/
author_profile: true
---

My articles can also be found on [my Google Scholar profile](https://scholar.google.com/citations?user=ubB7qwgAAAAJ&hl=en).

2018
------
**Sanchez, Jose**, Carlos M. Mateo, Juan Antonio Corrales, Belhassen-Chedli Bouzgarrou, and Youcef Mezouar. 
"Online Shape Tracking based on Tactile Sensing and Deformation Modeling for Robot Manipulation."
To appear in _IEEE/RSJ International Conference on Intelligent Robots and Systems_ (IROS), 2018.

Mohy el Dine<sup>[1](#myfootnote1)</sup>, Kamal, **Jose Sanchez**<sup>[1](#myfootnote1)</sup>, Juan Antonio Corrales, Youcef Mezouar, Jean-Christophe Fauroux.
"Force-Torque Sensor Disturbance Observer using Deep Learning."
Accepted in _International Symposium on Experimental Robotics_ (ISER), 2018.

**Sanchez, Jose**, Juan Antonio Corrales, Belhassen-Chedli Bouzgarrou, and Youcef Mezouar. 
"Robotic manipulation and sensing of deformable objects in domestic and industrial applications: a survey." 
In _The International Journal of Robotics Research_, Vol 37, Issue 7, 2018.


2016
------
**Sanchez, Jose**, Sven Schneider, Nico Hochgeschwender, Gerhard K. Kraetzschmar, and Paul G. Plöger. 
"Context-Based Adaptation of In-Hand Slip Detection for Service Robots." 
In _IFAC-PapersOnLine_ 49, no. 15 (2016): 266-271.

2014
------
**Sanchez, Jose**, Sven Schneider, and Paul Plöger. 
"Safely grasping with complex dexterous hands by tactile feedback."
In _Robot Soccer World Cup_, pp. 332-344. Springer, Cham, 2014.


<a name="myfootnote1">1</a>: First co-authors.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}


{% for post in site.publications reversed %}
  {% include archive-single.html type="mylist" %}
{% endfor %}

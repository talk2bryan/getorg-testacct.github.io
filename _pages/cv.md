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
* B.Sc. in Computer Science, University of Manitoba, 2018
* M.Sc. in Computer Science, University of Manitoba, 2020 (expected)

Work experience
======
* Fall 2018: Teaching Assistant
  * Dept. of Computer Science, University of Manitoba
  * Duties include:
    * Conducting class tutorials, debugging students’ code, and evaluating submissions.

* Summer 2018: Software Engineer Co-Op (Co-op Work Term III)
  * Electronic Arts
  * Duties included:
    * Maintained and created tools for the content delivery pipeline.
    * Validated Live content data, as well as system failures from a prioritized backlog.

* Fall 2014 - Winter 2018: Teaching Assistant
  * Dept. of Computer Science, University of Manitoba
  * Courses are listed in detail in the <u><a href="{{collections.teaching}}">Teaching</a> tab.</u>

* Summer 2017: Research Assistant (Co-op Work Term II)
  * Database & Data Mining Laboratory, University of Manitoba
  * Duties included: Created an orientation-free frequent pattern visualizer for Big Data, using D3.js. The goal was to enhance collaboration among users which, from my research on other visualization tools, was a common limitation.
  * Supervisor: [Dr. Carson K. Leung](http://www.cs.umanitoba.ca/~kleung/ "Dr. Carson K. Leung's Homepage")

* Winter 2017: Software Engineering Intern (Co-op Work Term I)
  * Google Inc.
  * Duties included:
    * Created a dashboard to view/query usage, demand, and supply of resources (cpu, disk, millicpu, milligpu) across clusters in different regions. 
    * Facilitated content migration by providing an export feature of said data to spreadsheets.
  
Skills
======
* Programming Languages
  * Java, C/C++, Haxe, Python, HTML/CSS, Javascript, SQL, R, Ruby
* Frameworks
  * Rails, CUDA, ROBOTIS
* Databases
  * MySQL, HSQLDB
* DevOps
  * Nginx, AWS, Docker, Vagrant, Capistrano
* Operating Systems
  * \*nix and Windows
* Version Control
  * Git, Perforce, svn
* Miscellenous
  * Jira, TravisCI, JProfiler, OpenCV, gdb, intelliJ, VS Code

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

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
* Ph.D in Mathematics, Boston University, 2022
* B.A. in Mathematics, Rutgers University - New Brunswick, 2016

Work experience
======
* 2024 - Current: AI Trainer
  * DataAnnotation
  * Duties include: Creating STEM/coding prompts for evaluating LLM responses, Evaluating and correcting LLM responses to STEM/coding prompts, Quality control testing the work of other trainers

* 2023 - 2024: Math Tutor
  * Varsity Tutors
  * Duties included: Tutoring graduate, undergraduate, and high school students in advanced mathematics

* 2022 - 2023: Part Time Math Lecturer
  * Northeastern University
  * Duties included: Lecturing, Creating Class Materials, Grading Exams and Homeworks, Holding Office Hours
  * Supervisor: Dr. Beth Smith

* 2017 - 2022: Teaching Assistant
  * Boston University
  * Duties included: Leading Recitations, Grading Exams and Homeworks, Holding Office Hours
  * Supervisor: Professor Panth

* Summer 2015: High Performance Computing Research Assistant
  * University of Maryland - Baltimore Country
  * Duties included: Parallelizing statistical software for the U.S. Census Bureau
  * Supervisor: Professor Adragni
  
Skills
======
* Mathematics
* Research
* Python
  * Numpy
  * Pandas
* Data Science
* Machine Learning
  * NLP (Natural Language Processing)
    
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
* Former President of the Boston University branch of the AMS Graduate Student organization

---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

My <a href ="{{ site.baseurl }}/files/Aditya_Karan_Jan25_CV_version_online.pdf"> resume </a> as a PDF

Education
======
* Ph.D in Computer Science, University of Illinois at Urbana Champaign, Dec 2025 (expected)
* M.S. in Computational Science and Engineering, Harvard University, 2020
* B.S. (with Honors) in Computer Science & Applied and Computational Mathematics, California Institute of Technology, 2016

Work Experience
======

## Permanent Positions 

* July 2016 - July 2018: Strat in Global Liquidity Products at Goldman Sachs 
  * Modeled forward looking funding requirements as required by Federal Reserves's Comprehensive Capital Analysis and Review process (CCAR) and the consequences to Funds Transfer Pricing (FTP) management.
  * Implemented various aspect of FTP framework to incentive prudent spot and contingent liquidity risk management  
  * Systematizing and automatic calculation and evaluation of internal liquidity metrics
  * Repo pricing under various liquidity and funding constraints.



## Industry Internships

* Summer 2024: Applied Science Intern at [Vijil](https://www.vijil.ai/)
  * Implemented a general pipeline for optimizing benchmark evaluations for large LLM benchmark (DecodingTrust, OpenLLM, etc) to give an
accurate estimate of trust of an LLM more efficiently 
  
* Summer 2023: Machine Learning PhD Intern at [Instacart](https://tech.instacart.com/the-economics-team-at-instacart-94c48db951e8)
  * Initiated and developed a more personalized payment authorization amount per user with $10MM estimated impact
  * Built a framework a generic contextual bandit process to perform automatic feature selection and mining through
existing experiments for heterogeneous treatment effect

* Summer 2022: Applied Research Intern at [Snap](https://snap.com/en-US)
=  * Developed a POC on joint user segmentation and retention modeling for subgroup analysis 
  * Provided Meaningful insights on user content preferences that tend to correlate higher retention

* Summer 2020: Software Engineering Intern at [Papaya](https://papayapay.com/)
  * Implemented a generic payment tool to automatically make web payments without human intervention 
  
* Summer 2019: Intern  at [Terrafuse AI](https://www.terrafuse-ai.com/)
  * Developed market design for wildfire risk for commercialization of high resolution climate forecasting 


<!-- Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3 -->

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
* Program Committee Member for FAccT 2025
* Program Committee Member for AIES 2024
* CMAP Citizen Advisory Board Member 2022-
* IMSA Alumni Board Member 2017-2018
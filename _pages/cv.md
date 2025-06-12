---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
 
[Download (PDF)](https://chefs-kiss.github.io/website/files/Mandery_CV_2025.pdf){: .btn }


Education
======
* M.S. in Applied and Computational Mathematics, University of Minnesota - Duluth, 2021
* B.S. in Applied Mathematics, University of Minnesota - Duluth, 2017
* B.S. in Statistics and Actuarial Science, University of Minnesota - Duluth, 2017

Work experience
======
* **Instructor of Computer Science** *St. Olaf College* (2022 - present)
  * Designed active learning curriculum and presented lectures for math and computer science courses.
  * Encouraged a growth mindset in others by mentoring and guiding students in developing computational skills and encouraging exploration and experimentation in courses taught.
  * Faculty mentor to student researchers involved in data competitions, hackathons, and machine learning projects.
  * Courses taught: Calculus I-II, Principles of Computer Science, Machine Learning, Ethics in Computer Science

* **Data Scientist** *Hennepin County* (2023 - 2024)
  * Sourced, aggregated, managed data and leveraged data science technologies to answer business questions as part of the imple- mentation of an enterprise integrated data system (EIDS) with a focus on building well-documented analysis pipelines.
  * Produced timely and relevant county-wide insights and data resources to support organization priorities, specifically around disparity reduction, and fostered action aimed at improving service delivery and outcomes for county residents.
  * Key projects: Investor-involved residential property sales, county-wide program involvement dashboard geared towards execu- tives, education and youth program intersections analysis health insurance linkage.
  * Data product environments: Azure, Databricks, R, Python, SQL, PowerBI, Neo4j

* **Pricing Analyst II** *Swanson Health Products* (2021 - 2023)
  * Identified weekly promotional prices on over 8,000 products to increase customer traffic across paid, natural, and catalog markets.
  * Ran clustering analysis to reclassify KVI segments for 18,000 products using sales trends and e-commerce metrics.
  * Led pricing evaluation for 1,600 products across ten global markets, reducing potential impact with elasticity forecasting models.
  * Presented strategic recommendations and insights to senior leadership through dynamic dashboards.
  * Data product environments: Snowflake, R, SQL, PowerBI
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
      {% if post.semesters %}
    <em>Taught in:</em>
    <ul>
      {% for semester in post.semesters %}
        <li>{{ semester }}</li>
      {% endfor %}
    </ul>
    {% endif %}
  {% endfor %}</ul>

Community Involvement
======
* Judge for COMAP Mathematical Contest in Modeling (MCM), 2018-2025
* Advisor and judge for MinneAnalytics MinneMUDAC data competition, 2024-2025
* GRE Quantitative Prep Tutor for TRIO McNair Scholars at University of Wisconsin - Superior, 2021 
* Volunteer at Mayo Clinic, 2018
* Gardener at Glensheen historic estate, 2017-2018

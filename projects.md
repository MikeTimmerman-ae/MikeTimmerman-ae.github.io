---
layout: project_home
title: "Projects"
list_title:
  - Classical Control
  - Learning-Based Control
  - Simulation & Modeling
  - Hardware & Flight Software
permalink: /projects/
---

<p>
    Below you find a collection of the projects I completed throughout my university education. They range from independent study, to course projects and research at a university lab. They are subdivided according to the following categories:
    <ul>
        {% for category in page.list_title %}
            <li><a href="#{{ category | slugify }}">{{ category }}</a></li>
        {% endfor %}
    </ul>
</p>

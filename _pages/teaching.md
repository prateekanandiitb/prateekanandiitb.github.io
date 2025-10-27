---
layout: page
permalink: /teaching/
title: Teaching
description: Course Materials
nav: true
nav_order: 4
---

We teach courses at undergraduate and graduate levels. Below are recent offerings.

<div class="row row-cols-1 row-cols-md-2 row-cols-lg-3 g-4 mt-3">
  {% assign sorted_courses = site.courses | sort: "order" %}
  {% for course in sorted_courses %}
    {% include courses.liquid course=course %}
  {% endfor %}
</div>

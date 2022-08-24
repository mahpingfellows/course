---
layout: page
title: Staff
description: A listing of all the course staff members.
---

# Staff

Meet your instructors!

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign faculty_sponsors = site.staffers | where: 'role', 'Faculty Sponsors' %}
{% assign num_faculty_sponsors= faculty_sponsors | size %}
{% if num_faculty_sponsors != 0 %}

## Faculty Sponsors

{% for staffer in faculty_sponsors %}
{{ staffer }}
{% endfor %}
{% endif %}

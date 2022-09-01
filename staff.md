---
layout: page
title: Staff
description: A listing of all the course staff members.
---

# Staff

Meet your instructors and faculty sponsors!

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Faculty Sponsors

{% assign faculty_sponsors = site.staffers | where: 'role', 'Faculty Sponsors' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

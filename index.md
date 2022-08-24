---
layout: home
title: Home
nav_exclude: false
nav_order: 1
seo:
  type: Course
  name: From Bench to Bedside
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

**Instructors:**  Mikaili Abdullah (MSM), Brittany Bush (MSM), Ben Finander (HMS), Lucy Lai (HMS), Jackie Lin (MSM), Lauren Miner (HMS), and Rachel Swope (HMS)

**Dates:** 
* September 21-23 @ Morehouse School of Medicine
* November 2-4 @ Harvard Medical School


{% for module in site.modules %}
{{ module }}
{% endfor %}

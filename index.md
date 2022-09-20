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

Circadian rhythms have a profound impact on our health and well being. Beyond regulating our sleep, they influence cognitive alertness, gastric motility, and cardiovascular health and many other body processes. Yet, our industrialized, 24/7 world often brings us out of sync with these rhythms leading to pervasive but addressable health consequences. Join us to learn the molecular and circuit mechanisms that sync our circadian rhythms to environmental cues like light and food, how our everyday activities and societal issues impact these rhythms, and how we can make policies to keep our circadian health intact without sacrificing all the amenities of modern life. This course is offered through the [Morehouse and Harvard Partnership in Neuroscience Growth (MAHPING) Pedagogy Fellows Program](https://projects.iq.harvard.edu/mahping/pedagogy-fellows-program).

**Instructors:**  Mikaili Abdullah (MSM), Brittany Bush (MSM), Ben Finander (HMS), Lucy Lai (HMS), Jackie Lin (MSM), Lauren Miner (HMS), and Rachel Swope (HMS). To learn more about your instructors, visit the [Staff](https://mahpingfellows.github.io/course/staff/) page!

**Dates:** 
* September 21-23 @ [Morehouse School of Medicine](https://msm.edu/)
* November 2-4 @ [Harvard Medical School](https://hms.harvard.edu/)


{% for module in site.modules %}
{{ module }}
{% endfor %}

---
layout: page
title: Calendar
description: Course calendar
---

# Weekly course calendar

You can attend classes on Zoom or in-person on the Caltech campus (pending sufficient interest). If you attend in person, please bring a laptop with you for in-class exercises.  

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}

---
layout: page
title: Schedule
description: Course schedule
---

# Weekly course schedule

Course dates are June 1 - July 15, 2026

You can attend classes on Zoom or in-person on the Caltech campus (pending sufficient interest). If you attend in person, please bring a laptop with you for in-class exercises. 

In addition to our weekly meetings, our course will end with a half-day symposium on July 18 or 19.

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}

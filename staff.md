---
layout: page
title: Staff
description: A listing of all the course staff members.
---

# Staff

## Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign guest_lecturers = site.staffers | where: 'role', 'Guest Lecturer' %}
{% assign num_guest_lecturers = guest_lecturers | size %}
{% if num_guest_lecturers != 0 %}

## Guest lecturers 

{% for staffer in guest_lecturers %}
{{ staffer }}
{% endfor %}
{% endif %}

{% assign project_mentors = site.staffers | where: 'role', 'Mentor' %}
{% assign num_project_mentors = project_mentors | size %}
{% if num_project_mentors != 0 %}

## Project mentors 

{% for staffer in project_mentors %}
{{ staffer }}
{% endfor %}
{% endif %}

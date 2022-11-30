---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
classes: wide
---

Clicking on any of the links below will redirect you to the abstract and details of my contributions.

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}

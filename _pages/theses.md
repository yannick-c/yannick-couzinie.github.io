---
layout: archive
title: "Theses"
permalink: /theses/
author_profile: true
---

{% include base_path %}

{% for post in site.theses reversed %}
  {% include archive-single.html %}
{% endfor %}

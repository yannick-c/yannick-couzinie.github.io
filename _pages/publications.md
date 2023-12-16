---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% else %}
  You can also find my articles on <a href="https://arxiv.org/search/math?searchtype=author&query=Couzini%C3%A9%2C+Y">arXiv</a>.
{% endif %}

Note: Papers with a star at the end are papers I did not first-author.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

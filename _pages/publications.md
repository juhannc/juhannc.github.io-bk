---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Conferences

{% for post in site.publications.conferences reversed %}
  {% include archive-single.html %}
{% endfor %}

## Theses

{% for post in site.publications.these reversed %}
  {% include archive-single.html %}
{% endfor %}

---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

## Conferences

{% include base_path/conferences %}

## Theses

{% include base_path/theses %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

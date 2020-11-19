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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Journal Articles
{% for post in site.publications reversed %}
  {% if post.collection == 'journal' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Conference Papers
{% for post in site.publications reversed %}
  {% if post.collection == 'conference' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Academic
{% for post in site.publications reversed %}
  {% if post.collection == 'academic' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

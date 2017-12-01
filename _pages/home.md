---
permalink: /
title: "Homepage"
excerpt: "About me"
author_profile: true
redirect_from: 
---
Publications
======

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Getting started
======

Create content & metadata
------


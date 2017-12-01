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
{% include site.pages.publications.md}


Getting started
======

Create content & metadata
------


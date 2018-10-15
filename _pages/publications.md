---
layout: archive
title: "Selected publications"
permalink: /publications/
author_profile: true
---

My articles can also be found on [my Google Scholar profile](https://scholar.google.com/citations?user=ubB7qwgAAAAJ&hl=en).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% for post in site.publications reversed %}
  {% include archive-single.html type="mylist" %}
{% endfor %}

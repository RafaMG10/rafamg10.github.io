---
layout: publi
permalink: /publications/
title: Publications
description: I publish in highly competitive peer-reviewed conferences in the field of HCI (Most prestigious conferences like CHI, UIST, etc).
years: [2019, 2018, 2017, 2016, 1935]
---



{% include base_path %}

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single_publi.html %}

{% endfor %}

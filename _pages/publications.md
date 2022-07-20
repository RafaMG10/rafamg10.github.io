---
layout: publi
permalink: /publications/
title: Publications
description: I publish in highly competitive peer-reviewed conferences; SIGGRAPH, CHI, and UIST. In the field of HCI, SIGGRAPH, CHI, and UIST are the single most prestigious conferences, with lower acceptance rates and higher impact factors than any other venues. <span style="color:DarkSlateBlue"> <b> Click on the pictures to watch the videos. </b> </span> 
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

---
layout: archive
title: "Research" 
permalink: /research/
author_profile: true
---

This is a page not in the menu. You can use markdown in this page. Blah.


{% include base_path %}


{% for post in site.research %}
  {% include archive-single.html %}
{% endfor %}
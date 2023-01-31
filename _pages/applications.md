---
layout: archive
title: "Applications"
permalink: /applications/
author_profile: true
---

{% for post in site.applications reversed %}
  {% include archive-single.html %}
{% endfor %}
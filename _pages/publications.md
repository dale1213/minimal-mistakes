---
title: "Publications"
layout: single
permalink: /publications/
author_profile: false
---

Below are selected publications.

{% assign entries = site.publications | sort: 'year' | reverse %}
{% for post in entries %}
  {% include archive-single-row.html post=post %}
{% endfor %}


